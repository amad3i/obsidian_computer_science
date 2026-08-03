---
title: "Consistency (database systems)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Consistency_(database_systems)"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Distributed transaction]]"]
---

# Consistency (database systems)

In database systems, consistency (or correctness) refers to the requirement that any given database transaction must change affected data only in allowed ways. Any data written to the database must be valid according to all defined rules, including constraints, cascades, triggers, and any combination thereof.  This does not guarantee correctness of the transaction in all ways the application programmer might have wanted (that is the responsibility of application-level code) but merely that any programming errors cannot result in the violation of any defined database constraints.
In a distributed system, referencing CAP theorem, consistency can also be understood as after a successful write, update or delete of a Record, any read request immediately receives the latest value of the Record.

## Related

- [[Atomicity (database systems)]]
- [[Big data]]
- [[Big memory]]
- [[Commit (data management)]]
- [[Commitment ordering]]
- [[Concurrency control]]
- [[Data preservation]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Distributed transaction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Consistency_(database_systems)