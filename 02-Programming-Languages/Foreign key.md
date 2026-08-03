---
title: "Foreign key"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Foreign_key"
wikipedia_categories: ["Data modeling", "Database management systems", "Databases", "SQL"]
related: ["[[Data control language]]", "[[Data query language]]", "[[Database object]]", "[[Materialized view]]", "[[Synonym (database)]]", "[[Table (database)]]", "[[Armstrong's axioms]]", "[[Candidate key]]", "[[Column (database)]]", "[[Commit (data management)]]"]
---

# Foreign key

A foreign key is a set of attributes in a table that refers to the primary key of another table, linking these two tables. In the context of relational databases, a foreign key is subject to an inclusion dependency constraint that the tuples consisting of the foreign key attributes in one relation, R, must also exist in some other (not necessarily distinct) relation, S; furthermore that those attributes must also be a candidate key in S.
In other words, a foreign key is a set of attributes that references a candidate key. For example, a table called TEAM may have an attribute, MEMBER_NAME, which is a foreign key referencing a candidate key, PERSON_NAME, in the PERSON table. Since MEMBER_NAME is a foreign key, any value existing as the name of a member in TEAM must also exist as a person's name in the PERSON table; in other words, every member of a TEAM is also a PERSON.

## Related

- [[Data control language]]
- [[Data query language]]
- [[Database object]]
- [[Materialized view]]
- [[Synonym (database)]]
- [[Table (database)]]
- [[Armstrong's axioms]]
- [[Candidate key]]
- [[Column (database)]]
- [[Commit (data management)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Foreign_key