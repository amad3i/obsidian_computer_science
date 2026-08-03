---
title: "Superkey"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Superkey"
wikipedia_categories: ["Data modeling", "Database management systems"]
related: ["[[Armstrong's axioms]]", "[[Candidate key]]", "[[Column (database)]]", "[[Data control language]]", "[[Data query language]]", "[[Database normalization]]", "[[Database object]]", "[[Foreign key]]", "[[Materialized view]]", "[[Primary key]]"]
---

# Superkey

In the relational data model, a superkey is any set of attributes that uniquely identifies each tuple of a relation. Because superkey values are unique, tuples with the same superkey value must also have the same non-key attribute values. That is, non-key attributes are functionally dependent on the superkey.
The set of all attributes is always a superkey (the trivial superkey). Tuples in a relation are by definition unique, with duplicates removed after each operation, so the set of all attributes is always uniquely valued for every tuple. A candidate key (or minimal superkey) is a superkey that can't be reduced to a simpler superkey by removing an attribute.
For example, in an employee schema with attributes employeeID, name, job, and departmentID, if employeeID values are unique then employeeID combined with any or all of the other attributes can uniquely identify tuples in the table. Each combination, {employeeID}, {employeeID, name}, {employeeID, name, job}, and so on is a superkey. {employeeID} is a candidate key, since no subset of its attributes is also a superkey. {employeeID, name, job, departmentID} is the trivial superkey.
If attribute set K is a superkey of relation R, then at all times it is the case that the projection of R over K has the same cardinality as R itself.

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

- Wikipedia: https://en.wikipedia.org/wiki/Superkey