---
title: "Autocommit"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Autocommit"
wikipedia_categories: ["Databases"]
related: ["[[Altibase]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]", "[[Connection string]]"]
---

# Autocommit

In the context of data management, autocommit is a mode of operation of a database connection. Each individual database interaction (i.e., each SQL statement) submitted through the database connection in autocommit mode will be executed in its own transaction that is implicitly committed. A SQL statement executed in autocommit mode cannot be rolled back.
Autocommit mode incurs per-statement transaction overhead and can often lead to undesirable performance or resource utilization impact on the database. Nonetheless, in systems such as Microsoft SQL Server, as well as connection technologies such as ODBC and Microsoft OLE DB, autocommit mode is the default for all statements that change data, in order to ensure that individual statements will conform to the ACID (atomicity-consistency-isolation-durability) properties of transactions.
The alternative to autocommit mode (non-autocommit) means that the SQL client application itself is responsible for ending transactions explicitly via the commit or rollback SQL commands. Non-autocommit mode enables grouping of multiple data manipulation SQL commands into a single atomic transaction.
Some DBMS (e.g. MariaDB) force autocommit for every DDL statement, even in non-autocommit mode. In this case, before each DDL statement, previous DML statements in transaction are autocommitted. Each DDL statement is executed in its own new autocommit transaction.

## Related

- [[Altibase]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]
- [[Commitment ordering]]
- [[Common data model]]
- [[Composite index (database)]]
- [[Concurrency control]]
- [[Connection string]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Autocommit