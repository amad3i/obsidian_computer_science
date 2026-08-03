---
title: "Database refactoring"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Database_refactoring"
wikipedia_categories: ["Databases", "Extreme programming"]
related: ["[[Altibase]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Code refactoring]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]"]
---

# Database refactoring

A database refactoring is a simple change to a database schema that improves its design while retaining both its behavioral and informational semantics.  Database refactoring does not change the way data is interpreted or used and does not fix bugs or add new functionality.  Every refactoring to a database leaves the system in a working state, thus not causing maintenance lags, provided the meaningful data exists in the production environment.   
A database refactoring is conceptually more difficult than a code refactoring; code refactorings only need to maintain behavioral semantics while database refactorings also must maintain informational semantics.
A database schema is typically refactored for one of several reasons:

To develop the schema in an evolutionary manner in parallel with the evolutionary design of the rest of the system.
To fix design problems with an existing legacy database schema. Database refactorings are often motivated by the desire for database normalization of an existing production database, typically to "clean up" the design of the database.
To implement what would be a large (and potentially risky) change as a series of small, low-risk changes.

## Related

- [[Altibase]]
- [[Autocommit]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]
- [[Code refactoring]]
- [[Commitment ordering]]
- [[Common data model]]
- [[Composite index (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Database_refactoring