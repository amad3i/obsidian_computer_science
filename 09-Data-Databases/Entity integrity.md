---
title: "Entity integrity"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Entity_integrity"
wikipedia_categories: ["Data modeling", "Data quality", "Database stubs"]
related: ["[[Column groups and row groups]]", "[[Data domain]]", "[[Golden record (informatics)]]", "[[Relvar]]", "[[Transition constraint]]", "[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Bitemporal modeling]]"]
---

# Entity integrity

Entity integrity is concerned with ensuring that each row of a table has a unique and non-null primary key value; this is the same as saying that each row in a table represents a single instance of the entity type modelled by the table. A requirement of E. F. Codd in his seminal paper is that a primary key of an entity, or any part of it, can never take a null value.
The relational model states that every relation (or table) must have an identifier, called the primary key (abbreviated PK), in such a way that every row of the same relation be identifiable by its content, that is, by a unique and minimal value. The PK is a not empty set of attributes (or columns). The same format applies to the foreign key (abbreviated FK) because each FK matches a preexistent PK. Each of attributes being part of a PK (or of a FK) must have data values (such as numbers, letters or typographic symbols) but not data marks (also known as NULL marks in SQL world). 
Morphologically, a composite primary key is in a "steady state": If it is reduced, PK will lose its property of identifying every row of its relation but if it is extended, PK will be redundant.

## Related

- [[Column groups and row groups]]
- [[Data domain]]
- [[Golden record (informatics)]]
- [[Relvar]]
- [[Transition constraint]]
- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]
- [[BIM Collaboration Format]]
- [[Bitemporal modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Entity_integrity