---
title: "Savepoint"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Savepoint"
wikipedia_categories: ["Data management", "Database management systems", "Transaction processing"]
related: ["[[Commit (data management)]]", "[[Concurrency control]]", "[[Multi-model database]]", "[[ACID]]", "[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commitment ordering]]", "[[Consistency (database systems)]]", "[[Data Analysis Expressions]]"]
---

# Savepoint

A savepoint is a way of implementing subtransactions (also known as nested transactions) within a relational database management system by indicating a point within a transaction that can be "rolled back to" without affecting any work done in the transaction before the savepoint was created. Multiple savepoints can exist within a single transaction. Savepoints are useful for implementing complex error recovery in database applications. If an error occurs in the midst of a multiple-statement transaction, the application may be able to recover from the error (by rolling back to a savepoint) without needing to abort the entire transaction.
A savepoint can be declared by issuing a SAVEPOINT name statement. All changes made after a savepoint has been declared can be undone by issuing a ROLLBACK TO SAVEPOINT name command. Issuing RELEASE SAVEPOINT name will cause the named savepoint to be discarded, but will not otherwise affect anything. Issuing the commands ROLLBACK or COMMIT will also discard any savepoints created since the start of the main transaction.
Savepoints are defined in the SQL standard and are supported by all established SQL relational databases, including PostgreSQL, Oracle Database, Microsoft SQL Server, MySQL, IBM Db2, SQLite (since 3.6.8), Firebird, H2 Database Engine, and Informix (since version 11.50xC3).

## Related

- [[Commit (data management)]]
- [[Concurrency control]]
- [[Multi-model database]]
- [[ACID]]
- [[Atomicity (database systems)]]
- [[Big data]]
- [[Big memory]]
- [[Commitment ordering]]
- [[Consistency (database systems)]]
- [[Data Analysis Expressions]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Savepoint