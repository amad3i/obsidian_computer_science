---
title: "Apache CouchDB"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Apache_CouchDB"
wikipedia_categories: ["2005 software", "Apache Software Foundation projects", "Client-server database management systems", "Cross-platform software", "Database-related software for Linux", "Distributed computing architecture", "Document-oriented databases", "Erlang (programming language)"]
related: ["[[Couchbase Server]]", "[[Virtuoso Universal Server]]", "[[Aerospike (database)]]", "[[ArangoDB]]", "[[Clusterpoint]]", "[[MongoDB]]", "[[Apache Accumulo]]", "[[Apache Samza]]", "[[Apache Storm]]", "[[CUBRID]]"]
---

# Apache CouchDB

Apache CouchDB is an open-source document-oriented NoSQL database, implemented in Erlang.
CouchDB uses multiple formats and protocols to store, transfer, and process its data. It uses JSON to store data, JavaScript as its query language using MapReduce, and HTTP for an API.
CouchDB was first released in 2005 and later became an Apache Software Foundation project in 2008.
Unlike a relational database, a CouchDB database does not store data and relationships in tables. Instead, each database is a collection of independent documents. Each document maintains its own data and self-contained schema. An application may access multiple databases, such as one stored on a user's mobile phone and another on a server. Document metadata contains revision information, making it possible to merge any differences that may have occurred while the databases were disconnected.
CouchDB implements a form of multiversion concurrency control (MVCC) so it does not lock the database file during writes. Conflicts are left to the application to resolve. Resolving a conflict generally involves first merging data into one of the documents, then deleting the stale one.
Other features include document-level ACID semantics with eventual consistency, (incremental) MapReduce, and (incremental) replication. One of CouchDB's distinguishing features is multi-master replication, which allows it to scale across machines to build high-performance systems.  A built-in Web application called Fauxton (formerly Futon) helps with administration.

## Related

- [[Couchbase Server]]
- [[Virtuoso Universal Server]]
- [[Aerospike (database)]]
- [[ArangoDB]]
- [[Clusterpoint]]
- [[MongoDB]]
- [[Apache Accumulo]]
- [[Apache Samza]]
- [[Apache Storm]]
- [[CUBRID]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Apache_CouchDB