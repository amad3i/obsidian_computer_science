---
title: "Snapshot isolation"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Snapshot_isolation"
wikipedia_categories: ["Concurrency control", "Databases", "Transaction processing"]
related: ["[[Commitment ordering]]", "[[Concurrency control]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Global serializability]]", "[[Index locking]]", "[[Locks with ordered sharing]]", "[[Two-phase locking]]", "[[ACID]]", "[[Advanced Synchronization Facility]]"]
---

# Snapshot isolation

In databases, and transaction processing (transaction management), snapshot isolation is a guarantee that all reads made in a transaction will see a consistent snapshot of the database (in practice it reads the last committed values that existed at the time it started), and the transaction itself will successfully commit only if no updates it has made conflict with any concurrent updates made since that snapshot.
Snapshot isolation has been adopted by several major database management systems, such as InterBase, Firebird, Oracle, MySQL, PostgreSQL, SQL Anywhere, MongoDB and Microsoft SQL Server (2005 and later). The main reason for its adoption is that it allows better performance than serializability, yet still avoids most of the concurrency anomalies that serializability avoids (but not all). In practice snapshot isolation is implemented within multiversion concurrency control (MVCC), where generational values of each data item (versions) are maintained: MVCC is a common way to increase concurrency and performance by generating a new version of a database object each time the object is written, and allowing transactions' read operations of several last relevant versions (of each object).  Snapshot isolation has been used to criticize the ANSI SQL-92 standard's definition of isolation levels, as it exhibits none of the "anomalies" that the SQL standard prohibited, yet is not serializable (the anomaly-free isolation level defined by ANSI).
In spite of its distinction from serializability, snapshot isolation is sometimes referred to as serializable by Oracle.

## Related

- [[Commitment ordering]]
- [[Concurrency control]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Global serializability]]
- [[Index locking]]
- [[Locks with ordered sharing]]
- [[Two-phase locking]]
- [[ACID]]
- [[Advanced Synchronization Facility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Snapshot_isolation