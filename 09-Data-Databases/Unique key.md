---
title: "Unique key"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Unique_key"
wikipedia_categories: ["Data modeling", "Database management systems"]
related: ["[[Armstrong's axioms]]", "[[Candidate key]]", "[[Column (database)]]", "[[Data control language]]", "[[Data query language]]", "[[Database normalization]]", "[[Database object]]", "[[Foreign key]]", "[[Materialized view]]", "[[Primary key]]"]
---

# Unique key

In relational database management systems, a unique key is a candidate key. All the candidate keys of a relation can uniquely identify the records of the relation, but only one of them is used as the primary key of the relation. The remaining candidate keys are called unique keys because they can uniquely identify a record in a relation. Unique keys can consist of multiple columns. Unique keys are also called alternate keys. Unique keys are an alternative to the primary key of the relation. In SQL, the unique keys have a UNIQUE constraint assigned to them in order to prevent duplicates (a duplicate entry is not valid in a unique column). Alternate keys may be used like the primary key when doing a single-table select or when filtering in a where clause, but are not typically used to join multiple tables.

## Related

- [[Armstrong's axioms]]
- [[Candidate key]]
- [[Column (database)]]
- [[Data control language]]
- [[Data query language]]
- [[Database normalization]]
- [[Database object]]
- [[Foreign key]]
- [[Materialized view]]
- [[Primary key]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unique_key