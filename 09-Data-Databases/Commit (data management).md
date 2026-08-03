---
title: "Commit (data management)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Commit_(data_management)"
wikipedia_categories: ["Data management", "Database management systems", "SQL", "Transaction processing"]
related: ["[[Concurrency control]]", "[[Multi-model database]]", "[[Savepoint]]", "[[ACID]]", "[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commitment ordering]]", "[[Consistency (database systems)]]", "[[Cursor (databases)]]"]
---

# Commit (data management)

In computer science and data management, a commit is a behavior that marks the end of a transaction and provides Atomicity, Consistency, Isolation, and Durability (ACID) in transactions. The submission records are stored in the submission log for recovery and consistency in case of failure. In terms of transactions, the opposite of committing is giving up tentative changes to the transaction, which is rolled back.
Due to the rise of distributed computing and the need to ensure data consistency across multiple systems, commit protocols have been evolving since their emergence in the 1970s. The main developments include the Two-Phase Commit (2PC) first proposed by Jim Gray, which is the fundamental core of distributed transaction management. Subsequently, the Three-phase Commit (3PC), Hypothesis Commit (PC), Hypothesis Abort (PA), and Optimistic Commit protocols gradually emerged, solving the problems of blocking and fault recovery.
Today, new fields such as e-commerce payment and blockchain technology are emerging, and submission protocols play a significant role in various business areas. By effectively handling transactions, resolving faults and recovering problems, the commit protocol becomes crucial in ensuring the reliability and consistency of data management.

## Related

- [[Concurrency control]]
- [[Multi-model database]]
- [[Savepoint]]
- [[ACID]]
- [[Atomicity (database systems)]]
- [[Big data]]
- [[Big memory]]
- [[Commitment ordering]]
- [[Consistency (database systems)]]
- [[Cursor (databases)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Commit_(data_management)