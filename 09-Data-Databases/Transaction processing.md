---
title: "Transaction processing"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Transaction_processing"
wikipedia_categories: ["Database management systems", "Fault-tolerant computer systems", "Transaction processing"]
related: ["[[ACID]]", "[[Commit (data management)]]", "[[Concurrency control]]", "[[In-database processing]]", "[[Multi-model database]]", "[[Online transaction processing]]", "[[Quorum (distributed computing)]]", "[[Replication (computing)]]", "[[Rollback (data management)]]", "[[Savepoint]]"]
---

# Transaction processing

In computer science, transaction processing is information processing that is divided into individual, indivisible operations called transactions. Each transaction must succeed or fail as a complete unit; it can never be only partially complete.
For example, when you purchase a book from an online bookstore, you exchange money (in the form of credit) for a book. If your credit is good, a series of related operations ensures that you get the book and the bookstore gets your money. However, if a single operation in the series fails during the exchange, the entire exchange fails. You do not get the book and the bookstore does not get your money. The technology responsible for making the exchange balanced and predictable is called transaction processing. Transactions ensure that data-oriented resources are not permanently updated unless all operations within the transactional unit complete successfully. By combining a set of related operations into a unit that either completely succeeds or completely fails, one can simplify error recovery and make one's application more reliable.
Transaction processing systems consist of computer hardware and software hosting a transaction-oriented application that performs the routine transactions necessary to conduct business. Examples include systems that manage sales order entry, airline reservations, payroll, employee records, manufacturing, and shipping.
Since most, though not necessarily all, transaction processing today is interactive, the term is often treated as synonymous with online transaction processing.

## Related

- [[ACID]]
- [[Commit (data management)]]
- [[Concurrency control]]
- [[In-database processing]]
- [[Multi-model database]]
- [[Online transaction processing]]
- [[Quorum (distributed computing)]]
- [[Replication (computing)]]
- [[Rollback (data management)]]
- [[Savepoint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transaction_processing