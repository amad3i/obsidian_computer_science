---
title: "Relational algebra"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Relational_algebra"
wikipedia_categories: ["Database management systems", "Relational algebra", "Relational model"]
related: ["[[Candidate key]]", "[[Database normalization]]", "[[Imieliński–Lipski algebra]]", "[[Materialized view]]", "[[Relation (database)]]", "[[Relational calculus]]", "[[Relational model]]", "[[Row (database)]]", "[[Sargable]]", "[[ACID]]"]
---

# Relational algebra

In database theory, relational algebra is a theory that uses algebraic structures for modeling data and defining queries on it with well founded semantics. The theory was introduced by Edgar F. Codd.
The main application of relational algebra is to provide a theoretical foundation for relational databases, particularly query languages for such databases, chief among which is SQL. Relational databases store tabular data represented as relations. Queries over relational databases often likewise return tabular data represented as relations.
The main purpose of relational algebra is to define operators that transform one or more input relations to an output relation. Given that these operators accept relations as input and produce relations as output, they can be combined and used to express complex queries that transform multiple input relations (whose data are stored in the database) into a single output relation (the query results).
Unary operators accept a single relation as input. Examples include operators to filter certain attributes (columns) or tuples (rows) from an input relation. Binary operators accept two relations as input and combine them into a single output relation. For example, taking all tuples found in either relation (union), removing tuples from the first relation found in the second relation (difference), extending the tuples of the first relation with tuples in the second relation matching certain conditions, and so forth.

## Related

- [[Candidate key]]
- [[Database normalization]]
- [[Imieliński–Lipski algebra]]
- [[Materialized view]]
- [[Relation (database)]]
- [[Relational calculus]]
- [[Relational model]]
- [[Row (database)]]
- [[Sargable]]
- [[ACID]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Relational_algebra