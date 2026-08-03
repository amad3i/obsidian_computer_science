---
title: "Imieliński–Lipski algebra"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Imieliński–Lipski_algebra"
wikipedia_categories: ["Database management systems", "Database theory", "Databases", "Relational model", "Types of databases"]
related: ["[[Database design]]", "[[Document-oriented database]]", "[[Key–value database]]", "[[Materialized view]]", "[[Probabilistic database]]", "[[Triplestore]]", "[[Bidirectionalization]]", "[[Candidate key]]", "[[Codd's 12 rules]]", "[[Composite index (database)]]"]
---

# Imieliński–Lipski algebra

In database theory, Imieliński–Lipski algebra is an extension of relational algebra onto tables with different types of null values. It is used to operate on relations with incomplete information.
Imieliński–Lipski algebras are defined to satisfy precise conditions for semantically meaningful extension of the usual relational operators, such as projection, selection, union, and join, from operators on relations to operators on relations with various kinds of "null values".
These conditions require that the system be safe in the sense that no incorrect conclusion is derivable by using a specified subset F of the relational operators; and that it be complete in the sense that all valid conclusions expressible by relational expressions using operators in F are in fact derivable in this system.
For example, it is well known that the three-valued logic approach to deal with null values, supported treatment of nulls values by SQL is not complete, see Ullman book.
To show this, let T be:

Take SQL query Q

SQL query Q will return empty set (no results) under 3-valued semantics currently adopted by all variants of SQL. This is the case because in SQL, NULL is never equal to any constant – in this case, neither to “Spring” nor “Fall” nor “Winter” (if there is Winter semester in this school). NULL='Spring' will evaluate to MAYBE and so will NULL='Fall'. The disjunction MAYBE OR MAYBE evaluates to MAYBE (not TRUE). Thus Igor will not be part of the answer (and of course neither will Rohit). But Igor should be returned as the answer.
Indeed, regardless what semester Igor took the Networks class (no matter what was the unknown value of NULL), the selection condition will be true. This “Igor” will be missed by SQL and the SQL answer would be incomplete according to completeness requirements specified in Tomasz Imieliński, Witold Lipski, 'Incomplete Information in Relational Databases'. It is also argued there that 3-valued logic (TRUE, FALSE, MAYBE) can never provide guarantee of complete answer for tables with incomplete information.
Three algebras which satisfy conditions of safety and completeness are defined as Imielinski–Lipski algebras: the Codd-Tables algebra, the V-tables algebra and the Conditional tables (C-tables) algebra.

## Related

- [[Database design]]
- [[Document-oriented database]]
- [[Key–value database]]
- [[Materialized view]]
- [[Probabilistic database]]
- [[Triplestore]]
- [[Bidirectionalization]]
- [[Candidate key]]
- [[Codd's 12 rules]]
- [[Composite index (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Imieliński–Lipski_algebra