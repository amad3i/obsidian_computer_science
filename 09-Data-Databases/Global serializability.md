---
title: "Global serializability"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Global_serializability"
wikipedia_categories: ["Concurrency control", "Data management", "Databases", "Transaction processing"]
related: ["[[Commitment ordering]]", "[[Concurrency control]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Locks with ordered sharing]]", "[[Big data]]", "[[Index locking]]", "[[Multi-model database]]", "[[Snapshot isolation]]", "[[Two-phase locking]]"]
---

# Global serializability

In concurrency control of databases, transaction processing (transaction management), and other transactional distributed applications, global serializability (or modular serializability) is a property of a global schedule of transactions. A global schedule is the unified schedule of all the individual database (and other transactional object) schedules in a multidatabase environment (e.g., federated database). Complying with global serializability means that the global schedule is serializable, has the serializability property, while each component database (module) has a serializable schedule as well. In other words, a collection of serializable components provides overall system serializability, which is usually incorrect. A need in correctness across databases in multidatabase systems makes global serializability a major goal for global concurrency control (or modular concurrency control). With the proliferation of the Internet, Cloud computing, Grid computing, and small, portable, powerful computing devices (e.g., smartphones), as well as increase in systems management sophistication, the need for atomic distributed transactions and thus effective global serializability techniques, to ensure correctness in and among distributed transactional applications, seems to increase.
In a federated database system or any other more loosely defined multidatabase system, which are typically distributed in a communication network, transactions span multiple (and possibly distributed) databases. Enforcing global serializability in such system, where different databases may use different types of concurrency control, is problematic. Even if every local schedule of a single database is serializable, the global schedule of a whole system is not necessarily serializable. The massive communication exchanges of conflict information needed between databases to reach conflict serializability globally would lead to unacceptable performance, primarily due to computer and communication latency. Achieving global serializability effectively over different types of concurrency control has been open for several years.

## Related

- [[Commitment ordering]]
- [[Concurrency control]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Locks with ordered sharing]]
- [[Big data]]
- [[Index locking]]
- [[Multi-model database]]
- [[Snapshot isolation]]
- [[Two-phase locking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Global_serializability