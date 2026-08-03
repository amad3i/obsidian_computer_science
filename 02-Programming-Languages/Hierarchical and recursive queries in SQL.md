---
title: "Hierarchical and recursive queries in SQL"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Hierarchical_and_recursive_queries_in_SQL"
wikipedia_categories: ["Database management systems", "Recursion", "SQL"]
related: ["[[Commit (data management)]]", "[[Cursor (databases)]]", "[[Data control language]]", "[[Data query language]]", "[[Database object]]", "[[Foreign key]]", "[[Nested SQL]]", "[[Query optimization]]", "[[Query plan]]", "[[SQL]]"]
---

# Hierarchical and recursive queries in SQL

A hierarchical query is a type of SQL query that handles hierarchical model data. These are useful for working with databases of graph-structured data, such as river networks, file system trees, or threaded comments. They are special cases of more general recursive fixpoint queries, which compute transitive closures.
In standard SQL:1999 hierarchical queries are implemented by way of recursive common table expressions (CTEs). Unlike Oracle's earlier connect-by clause, recursive CTEs were designed with fixpoint semantics from the beginning. Recursive CTEs from the standard were relatively close to the existing implementation in IBM DB2 version 2. Recursive CTEs are also supported by Microsoft SQL Server (since SQL Server 2008 R2), Firebird 2.1, PostgreSQL 8.4+, SQLite 3.8.3+, IBM Informix version 11.50+, CUBRID, MariaDB 10.2+ and MySQL 8.0.1+. Tableau has documentation describing how CTEs can be used. TIBCO Spotfire does not support CTEs, while Oracle 11g Release 2's implementation lacks fixpoint semantics.
Without common table expressions or connected-by clauses it is possible to achieve hierarchical queries with user-defined recursive functions.

## Related

- [[Commit (data management)]]
- [[Cursor (databases)]]
- [[Data control language]]
- [[Data query language]]
- [[Database object]]
- [[Foreign key]]
- [[Nested SQL]]
- [[Query optimization]]
- [[Query plan]]
- [[SQL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hierarchical_and_recursive_queries_in_SQL