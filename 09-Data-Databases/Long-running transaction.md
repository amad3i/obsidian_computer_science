---
title: "Long-running transaction"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Long-running_transaction"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]"]
---

# Long-running transaction

Long-running transactions (also known as the saga interaction pattern) are computer database transactions that avoid locks on non-local resources, use compensation to handle failures, potentially aggregate smaller ACID transactions (also referred to as atomic transactions), and typically use a coordinator to complete or abort the transaction. In contrast to rollback in ACID transactions, compensation restores the original state, or an equivalent, and is business-specific. For example, the compensating action for making a hotel reservation is canceling that reservation.
A number of protocols have been specified for long-running transactions using Web services within business processes. OASIS Business Transaction Processing and WS-CAF are examples. These protocols use a coordinator to mediate the successful completion or use of compensation in a long-running transaction.

## Related

- [[Atomicity (database systems)]]
- [[Big data]]
- [[Big memory]]
- [[Commit (data management)]]
- [[Commitment ordering]]
- [[Concurrency control]]
- [[Consistency (database systems)]]
- [[Data preservation]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Long-running_transaction