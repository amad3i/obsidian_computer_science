---
title: "Materialized view"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Materialized_view"
wikipedia_categories: ["Data modeling", "Database management systems", "Databases", "Relational model"]
related: ["[[Candidate key]]", "[[Foreign key]]", "[[Imieliński–Lipski algebra]]", "[[Relvar]]", "[[Row (database)]]", "[[Synonym (database)]]", "[[Armstrong's axioms]]", "[[Cardinality (data modeling)]]", "[[Codd's 12 rules]]", "[[Column (database)]]"]
---

# Materialized view

In computing, a materialized view is a database object that contains the results of a query. For example, it may be a local copy of data located remotely, or may be a subset of the rows and/or columns of a table or join result, or may be a summary using an aggregate function.
The process of setting up a materialized view is sometimes called materialization. This is a form of caching the results of a query, similar to memoization of the value of a function in functional languages, and it is sometimes described as a form of precomputation. As with other forms of precomputation, database users typically use materialized views for performance reasons, i.e. as a form of optimization.
Materialized views that store data based on remote tables were also known as snapshots (deprecated Oracle terminology).
In any database management system following the relational model, a view is a virtual table representing the result of a database query. Whenever a query or an update addresses an ordinary view's virtual table, the DBMS converts these into queries or updates against the underlying base tables. A materialized view takes a different approach: the query result is cached as a concrete ("materialized") table (rather than a view as such) that may be updated from the original base tables from time to time. This enables much more efficient access, at the cost of extra storage and of some data being potentially out-of-date. Materialized views find use especially in data warehousing scenarios, where frequent queries of the actual base tables can be expensive.
In a materialized view, indexes can be built on any column. In contrast, in a normal view, it's typically only possible to exploit indexes on columns that come directly from (or have a mapping to) indexed columns in the base tables; often this functionality is not offered at all.

## Related

- [[Candidate key]]
- [[Foreign key]]
- [[Imieliński–Lipski algebra]]
- [[Relvar]]
- [[Row (database)]]
- [[Synonym (database)]]
- [[Armstrong's axioms]]
- [[Cardinality (data modeling)]]
- [[Codd's 12 rules]]
- [[Column (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Materialized_view