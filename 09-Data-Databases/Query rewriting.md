---
title: "Query rewriting"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Query_rewriting"
wikipedia_categories: ["Data management"]
related: ["[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]", "[[Association rule learning]]", "[[Astroinformatics]]"]
---

# Query rewriting

Query rewriting is a typically automatic transformation that takes a set of database tables, views, and/or queries, usually indices, often gathered data and query statistics, and other metadata, and yields a set of different queries, which produce the same results but execute with better performance (for example, faster, or with lower memory use). Query rewriting can be based on relational algebra or an extension thereof (e.g. multiset relational algebra with sorting, aggregation and three-valued predicates i.e. NULLs as in the case of SQL). The equivalence rules of relational algebra are exploited, in other words, different query structures and orderings can be mathematically proven to yield the same result. For example, filtering on fields A and B, or cross joining R and S can be done in any order, but there can be a performance difference. Multiple operations may be combined, and operation orders may be altered.
The result of query rewriting may not be at the same abstraction level or application programming interface (API) as the original set of queries (though often is). For example, the input queries may be in relational algebra or SQL, and the rewritten queries may be closer to the physical representation of the data, e.g. array operations. Query rewriting can also involve materialization of views and other subqueries; operations that may or may not be available to the API user. The query rewriting transformation can be aided by creating indices from which the optimizer can choose (some database systems create their own indexes if deemed useful), mandating the use of specific indices, creating materialized and/or denormalized views, or helping a database system gather statistics on the data and query use, as the optimality depends on patterns in data and typical query usage.
Query rewriting may be rule based or optimizer based. Some sources discuss query rewriting as a distinct step prior to optimization, operating at the level of the user accessible algebra API (e.g. SQL).
There are other, largely unrelated concepts also named similarly, for example, query rewriting by search engines.

## Related

- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Approximate inference]]
- [[Archive site]]
- [[Asset Description Metadata Schema]]
- [[Association rule learning]]
- [[Astroinformatics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Query_rewriting