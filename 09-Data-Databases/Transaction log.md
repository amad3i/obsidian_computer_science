---
title: "Transaction log"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Transaction_log"
wikipedia_categories: ["Computer logging", "Database management systems", "Transaction processing"]
related: ["[[ACID]]", "[[Commit (data management)]]", "[[Concurrency control]]", "[[In-database processing]]", "[[Multi-model database]]", "[[Online transaction processing]]", "[[Quorum (distributed computing)]]", "[[Rollback (data management)]]", "[[Savepoint]]", "[[Temporal database]]"]
---

# Transaction log

In the field of databases in computer science, a transaction log (also transaction journal, database log, binary log or audit trail) is a history of actions executed by a database management system used to guarantee ACID properties over crashes or hardware failures. Physically, a log is a file listing changes to the database, stored in a stable storage format.
If, after a start, the database is found in an inconsistent state or not been shut down properly, the database management system reviews the database logs for uncommitted transactions and rolls back the changes made by these transactions. Additionally, all transactions that are already committed but whose changes were not yet materialized in the database are re-applied. Both are done to ensure atomicity and durability of transactions.
This term is not to be confused with other, human-readable logs that a database management system usually provides.
In database management systems, a journal is the record of data altered by a given process.

## Related

- [[ACID]]
- [[Commit (data management)]]
- [[Concurrency control]]
- [[In-database processing]]
- [[Multi-model database]]
- [[Online transaction processing]]
- [[Quorum (distributed computing)]]
- [[Rollback (data management)]]
- [[Savepoint]]
- [[Temporal database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transaction_log