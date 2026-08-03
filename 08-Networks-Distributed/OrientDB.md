---
title: "OrientDB"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/OrientDB"
wikipedia_categories: ["Distributed computing architecture", "Document-oriented databases", "Free database management systems", "Graph databases", "NoSQL", "Structured storage"]
related: ["[[Apache CouchDB]]", "[[NebulaGraph]]", "[[RethinkDB]]", "[[SciDB]]", "[[Virtuoso Universal Server]]", "[[ArangoDB]]", "[[Couchbase Server]]", "[[JanusGraph]]", "[[MongoDB]]", "[[TerminusDB]]"]
---

# OrientDB

OrientDB is an open source NoSQL database management system written in Java. It is a Multi-model database, supporting graph, document and object models, the relationships are managed as in graph databases with direct connections between records. It supports schema-less, schema-full and schema-mixed modes. It has a strong security profiling system based on users and roles and supports querying with Gremlin along with SQL extended for graph traversal. OrientDB uses several indexing mechanisms based on B-tree and Extendible hashing, the last one is known as "hash index". Each record has Surrogate key which indicates the position of the record on disk. Links between records (edges) are stored either as the record's position stored directly inside of the referrer or as B-tree of record positions (so-called record IDs or RIDs), that serves as a container of RIDs, which allows fast traversal (with O(1) complexity) of one-to-many relationships and fast addition/removal of new links. OrientDB is the 6th most popular graph database according to the DB-Engines graph database ranking, as of January 2024.
The development of OrientDB relies on an open-source community. The project uses GitHub to manage the sources, contributors and versioning.

## Related

- [[Apache CouchDB]]
- [[NebulaGraph]]
- [[RethinkDB]]
- [[SciDB]]
- [[Virtuoso Universal Server]]
- [[ArangoDB]]
- [[Couchbase Server]]
- [[JanusGraph]]
- [[MongoDB]]
- [[TerminusDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/OrientDB