---
title: "Schema matching"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Schema_matching"
wikipedia_categories: ["Databases"]
related: ["[[Altibase]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]"]
---

# Schema matching

The terms schema matching and mapping are often used interchangeably for a database process. For this article, we differentiate the two as follows: schema matching is the process of identifying that two objects are semantically related (scope of this article) while mapping refers to the transformations between the objects. For example, in the two schemas DB1.Student (Name, SSN, Level, Major, Marks)
and DB2.Grad-Student (Name, ID, Major, Grades); possible matches would be: DB1.Student ≈ DB2.Grad-Student; DB1.SSN = DB2.ID etc. and possible transformations or mappings would be: DB1.Marks to DB2.Grades (100–90 A; 90–80 B: etc.).
Automating these two approaches has been one of the fundamental tasks of data integration. In general, it is not possible to determine fully automatically the different correspondences between two schemas — primarily because of the differing and often not explicated or documented semantics of the two schemas.

## Related

- [[Altibase]]
- [[Autocommit]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]
- [[Commitment ordering]]
- [[Common data model]]
- [[Composite index (database)]]
- [[Concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Schema_matching