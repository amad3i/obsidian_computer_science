---
title: "Database connection"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Database_connection"
wikipedia_categories: ["Databases"]
related: ["[[Altibase]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]"]
---

# Database connection

A database connection is a facility in computer science that allows client software to talk to database server software, whether on the same machine or not.  A connection is required to send commands and receive answers, usually in the form of a result set.
Connections are a key concept in data-centric programming. Since some DBMS engines require considerable time to connect, connection pooling was invented to improve performance.  No command can be performed against a database without an "open and available" connection to it.
Connections are built by supplying an underlying driver or provider with a connection string, which is a way of addressing a specific database or server and instance as well as user authentication credentials (for example, Server=sql_box;Database=Common;User ID=uid;Pwd=password;).  Once a connection has been built it can be opened and closed at will, and properties (such as the command time-out length, or transaction, if one exists) can be set. The Connection String is composed of a set of key/value pairs as dictated by the data access interface and data provider being used.
Many databases (such as PostgreSQL) only allow one operation to be performed at a time on each connection.  If a request for data (a SQL Select statement) is sent to the database and a result set is returned, the connection is open but not available for other operations until the client finishes consuming the result set. Other databases, like SQL Server 2005 (and later), do not impose this limitation. However, databases that provide multiple operations per connection usually incur far more overhead than those that permit only a single operation task at a time.

## Related

- [[Altibase]]
- [[Autocommit]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]
- [[Commitment ordering]]
- [[Common data model]]
- [[Composite index (database)]]
- [[Concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Database_connection