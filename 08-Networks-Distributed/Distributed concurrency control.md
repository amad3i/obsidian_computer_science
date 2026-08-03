---
title: "Distributed concurrency control"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_concurrency_control"
wikipedia_categories: ["Concurrency control", "Data management", "Databases", "Distributed computing problems", "Transaction processing"]
related: ["[[Database transaction schedule]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Global serializability]]", "[[Locks with ordered sharing]]", "[[Big data]]", "[[Big memory]]", "[[Index locking]]", "[[Multi-model database]]", "[[Snapshot isolation]]"]
---

# Distributed concurrency control

Distributed concurrency control is the concurrency control of a system distributed over a computer network (Bernstein et al. 1987, Weikum and Vossen 2001). 
In database systems and transaction processing (transaction management) distributed concurrency control refers primarily to the concurrency control of a distributed database. It also refers to the concurrency control in a multidatabase (and other multi-transactional object) environment (e.g., federated database, grid computing, and cloud computing environments. A major goal for distributed concurrency control is distributed serializability (or global serializability for multidatabase systems). Distributed concurrency control poses special challenges beyond centralized one, primarily due to communication and computer latency. It often requires special techniques, like distributed lock manager over fast computer networks with low latency, like switched fabric (e.g., InfiniBand).
The most common distributed concurrency control technique is strong strict two-phase locking (SS2PL, also named rigorousness), which is also a common centralized concurrency control technique. SS2PL provides both the serializability and strictness. Strictness, a special case of recoverability, is utilized for effective recovery from failure. For large-scale distribution and complex transactions, distributed locking's typical heavy performance penalty (due to delays, latency) can be saved by using the atomic commitment protocol, which is needed in a distributed database for (distributed) transactions' atomicity.

## Related

- [[Database transaction schedule]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_concurrency_control