---
title: "Query plan"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Query_plan"
wikipedia_categories: ["Database management systems", "SQL"]
related: ["[[Commit (data management)]]", "[[Cursor (databases)]]", "[[Data control language]]", "[[Data query language]]", "[[Database object]]", "[[Foreign key]]", "[[Hierarchical and recursive queries in SQL]]", "[[Nested SQL]]", "[[Query optimization]]", "[[SQL]]"]
---

# Query plan

A query plan (or query execution plan) is a sequence of steps used to access data in a SQL relational database management system. This is a specific case of the relational model concept of access plans.
Since SQL is declarative, there are typically many alternative ways to execute a given query, with widely varying performance. When a query is submitted to the database, the query optimizer evaluates some of the different, correct possible plans for executing the query and returns what it considers the best option. Because query optimizers are imperfect, database users and administrators sometimes need to manually examine and tune the plans produced by the optimizer to get better performance.

## Related

- [[Commit (data management)]]
- [[Cursor (databases)]]
- [[Data control language]]
- [[Data query language]]
- [[Database object]]
- [[Foreign key]]
- [[Hierarchical and recursive queries in SQL]]
- [[Nested SQL]]
- [[Query optimization]]
- [[SQL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Query_plan