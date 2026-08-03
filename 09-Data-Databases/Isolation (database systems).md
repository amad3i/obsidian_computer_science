---
title: "Isolation (database systems)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Isolation_(database_systems)"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]"]
---

# Isolation (database systems)

In database systems, isolation is one of the ACID (Atomicity, Consistency, Isolation, Durability) transaction properties. It determines how transaction integrity is visible to other users and systems. A lower isolation level increases the ability of many users to access the same data at the same time, but also increases the number of concurrency effects (such as  dirty reads or lost updates) users might encounter. Conversely, a higher isolation level reduces the types of concurrency effects that users may encounter, but requires more system resources and increases the chances that one transaction will block another.

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

- Wikipedia: https://en.wikipedia.org/wiki/Isolation_(database_systems)