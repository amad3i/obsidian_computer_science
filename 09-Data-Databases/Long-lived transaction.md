---
title: "Long-lived transaction"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Long-lived_transaction"
wikipedia_categories: ["Data management", "Software engineering stubs", "Transaction processing"]
related: ["[[Atomicity (database systems)]]", "[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]"]
---

# Long-lived transaction

A long-lived transaction is a transaction that spans multiple database transactions. The transaction is considered "long-lived" because its boundaries must, by necessity of business logic, extend past a single database transaction. A long-lived transaction can be thought of as a sequence of database transactions grouped to achieve a single atomic result.
A common example is a multi-step sequence of requests and responses of an interaction with a user through a web client.
A long-lived transaction creates challenges of concurrency control and scalability.
A chief strategy in designing long-lived transactions is optimistic concurrency control with versioning.

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

- Wikipedia: https://en.wikipedia.org/wiki/Long-lived_transaction