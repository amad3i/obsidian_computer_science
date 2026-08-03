---
title: "Natural key"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Natural_key"
wikipedia_categories: ["Data modeling"]
related: ["[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Bitemporal modeling]]", "[[Building information modeling]]", "[[BuildingSMART Data Dictionary]]", "[[Business rule management system]]", "[[Cadwork Engineer]]", "[[Candidate key]]"]
---

# Natural key

A natural key (also known as business key or domain key) is a type of unique key in a database formed of attributes that exist and are used in the external world outside the database (i.e. in the business domain or domain of discourse). In the relational model of data, a natural key is a superkey and is therefore a functional determinant for all attributes in a relation.
A natural key serves two complementary purposes: 

It provides a means of unique identification for data
It imposes a rule, specifically a uniqueness constraint, to ensure that data remains unique within an information system
The uniqueness constraint assures uniqueness of data within a certain technical context (e.g. a set of values in a table, file or relation variable) by rejecting input of any data that would otherwise violate the constraint. This means that the user can rely on a guaranteed correspondence between facts identified by key values recorded in a system and the external domain of discourse (a single version of the truth according to Kimball).
A natural key differs from a surrogate key which has no meaning outside the database itself and is not based on real-world observation or intended as a statement about the reality being modelled. A natural key therefore provides a certain data quality guarantee whereas a surrogate does not. It is common for elements of data to have several keys, any number of which may be natural or surrogate.

## Related

- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]
- [[BIM Collaboration Format]]
- [[Bitemporal modeling]]
- [[Building information modeling]]
- [[BuildingSMART Data Dictionary]]
- [[Business rule management system]]
- [[Cadwork Engineer]]
- [[Candidate key]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Natural_key