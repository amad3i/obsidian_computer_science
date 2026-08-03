---
title: "Candidate key"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Candidate_key"
wikipedia_categories: ["Data modeling", "Database management systems", "Relational model"]
related: ["[[Materialized view]]", "[[Row (database)]]", "[[Armstrong's axioms]]", "[[Cardinality (data modeling)]]", "[[Codd's 12 rules]]", "[[Column (database)]]", "[[Data control language]]", "[[Data query language]]", "[[Database normalization]]", "[[Database object]]"]
---

# Candidate key

A candidate key, or simply a key, of a relational database is any set of columns that have a unique combination of values in each row, with the additional constraint that removing any column could produce duplicate combinations of values.
A candidate key is a minimal superkey, 
i.e., a superkey that does not contain a smaller one. Therefore, a relation can have multiple candidate keys, each with a different number of attributes.
Specific candidate keys are sometimes called primary keys, secondary keys or alternate keys.
The columns in a candidate key are called prime attributes, and a column that does not occur in any candidate key is called a non-prime attribute.
Every relation without NULL values will have at least one candidate key: Since there cannot be duplicate rows, the set of all columns is a superkey, and if that is not minimal, some subset of that will be minimal.
There is a functional dependency from the candidate key to all the attributes in the relation.
The superkeys of a relation are all the possible ways we can identify a row. The candidate keys are the minimal subsets of each superkey and as such, they are an important concept for the design of database schema.

## Related

- [[Materialized view]]
- [[Row (database)]]
- [[Armstrong's axioms]]
- [[Cardinality (data modeling)]]
- [[Codd's 12 rules]]
- [[Column (database)]]
- [[Data control language]]
- [[Data query language]]
- [[Database normalization]]
- [[Database object]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Candidate_key