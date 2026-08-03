---
title: "Two-phase locking"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Two-phase_locking"
wikipedia_categories: ["Concurrency control", "Databases", "Transaction processing"]
related: ["[[Commitment ordering]]", "[[Concurrency control]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Global serializability]]", "[[Index locking]]", "[[Locks with ordered sharing]]", "[[Snapshot isolation]]", "[[ACID]]", "[[Advanced Synchronization Facility]]"]
---

# Two-phase locking

In databases and transaction processing, two-phase locking (2PL) is a pessimistic concurrency control method that guarantees conflict-serializability. It is also the name of the resulting set of database transaction schedules (histories). The protocol uses locks, applied by a transaction to data, which may block (interpreted as signals to stop) other transactions from accessing the same data during the transaction's life.
By the 2PL protocol, locks are applied and removed in two phases:

Expanding phase: locks are acquired and no locks are released.
Shrinking phase: locks are released and no locks are acquired.
Two types of locks are used by the basic protocol: Shared and Exclusive locks. Refinements of the basic protocol may use more lock types. Using locks that block processes, 2PL, S2PL, and SS2PL may be subject to deadlocks that result from the mutual blocking of two or more transactions.

## Related

- [[Commitment ordering]]
- [[Concurrency control]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Global serializability]]
- [[Index locking]]
- [[Locks with ordered sharing]]
- [[Snapshot isolation]]
- [[ACID]]
- [[Advanced Synchronization Facility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Two-phase_locking