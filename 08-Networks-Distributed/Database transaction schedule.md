---
title: "Database transaction schedule"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Database_transaction_schedule"
wikipedia_categories: ["Concurrency control", "Data management", "Databases", "Distributed computing problems", "NP-complete problems", "Transaction processing"]
related: ["[[Distributed concurrency control]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Global serializability]]", "[[Locks with ordered sharing]]", "[[Big data]]", "[[Big memory]]", "[[Index locking]]", "[[Multi-model database]]", "[[Snapshot isolation]]"]
---

# Database transaction schedule

In the fields of databases and transaction processing (transaction management), a schedule (or history) of a system is an abstract model to describe the order of executions in a set of transactions running in the system. Often it is a list of operations (actions) ordered by time, performed by a set of transactions that are executed together in the system. If the order in time between certain operations is not determined by the system, then a partial order is used. Examples of such operations are requesting a read operation, reading, writing, aborting, committing, requesting a lock, locking, etc. Often, only a subset of the transaction operation types are included in a schedule. 
Schedules are fundamental concepts in database concurrency control theory. In practice, most general purpose database systems employ conflict-serializable and strict recoverable schedules.

## Related

- [[Distributed concurrency control]]
- [[Commitment ordering]]
- [[Concurrency control]]
- [[Global serializability]]
- [[Locks with ordered sharing]]
- [[Big data]]
- [[Big memory]]
- [[Index locking]]
- [[Multi-model database]]
- [[Snapshot isolation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Database_transaction_schedule