---
title: "Compensating transaction"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Compensating_transaction"
wikipedia_categories: ["Data synchronization", "Distributed computing architecture", "Transaction processing"]
related: ["[[Multi-model database]]", "[[ACID]]", "[[Advanced Synchronization Facility]]", "[[Aerospike (database)]]", "[[Aggregate Level Simulation Protocol]]", "[[Altibase]]", "[[Amoeba (operating system)]]", "[[Andrew Project]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]"]
---

# Compensating transaction

In transaction processing and distributed computing, a compensating transaction is a transaction that reverses the effects of a previously committed transaction. It is a core concept in the saga design pattern, used to maintain data consistency across multiple services or databases in scenarios where traditional ACID transactions are not feasible or practical.
A compensating transaction is necessary when a business process, which may consist of several individual transactions, fails after one or more of its steps have already been successfully completed (committed). Unlike a database rollback, which discards uncommitted changes, a compensating transaction is a new transaction that applies business logic to semantically undo the work of a completed transaction, thereby restoring the system to a consistent state.

## Related

- [[Multi-model database]]
- [[ACID]]
- [[Advanced Synchronization Facility]]
- [[Aerospike (database)]]
- [[Aggregate Level Simulation Protocol]]
- [[Altibase]]
- [[Amoeba (operating system)]]
- [[Andrew Project]]
- [[Apache Accumulo]]
- [[Apache CouchDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Compensating_transaction