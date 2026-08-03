---
title: "Rollback (data management)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Rollback_(data_management)"
wikipedia_categories: ["Database management systems", "Database theory", "Reversible computing", "Transaction processing"]
related: ["[[Temporal database]]", "[[ACID]]", "[[Bidirectionalization]]", "[[Commit (data management)]]", "[[Concurrency control]]", "[[Database design]]", "[[Database theory]]", "[[Imieliński–Lipski algebra]]", "[[In-database processing]]", "[[Multi-model database]]"]
---

# Rollback (data management)

In database technologies, a rollback is an operation which returns the database to some previous state. Rollbacks are important for database integrity, because they mean that the database can be restored to a clean copy even after erroneous operations are performed. They are crucial for recovering from database server crashes; by rolling back any transaction which was active at the time of the crash, the database is restored to a consistent state.
The rollback feature is usually implemented with a transaction log, but can also be implemented via multiversion concurrency control.

## Related

- [[Temporal database]]
- [[ACID]]
- [[Bidirectionalization]]
- [[Commit (data management)]]
- [[Concurrency control]]
- [[Database design]]
- [[Database theory]]
- [[Imieliński–Lipski algebra]]
- [[In-database processing]]
- [[Multi-model database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rollback_(data_management)