---
title: "Associative entity"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Associative_entity"
wikipedia_categories: ["Diagrams", "Entity–relationship model"]
related: ["[[Activity cycle diagram]]", "[[And-inverter graph]]", "[[Binary decision diagram]]", "[[C4 model]]", "[[Commutative diagram]]", "[[Concept map]]", "[[Conceptual graph]]", "[[Control-flow diagram]]", "[[Data-flow diagram]]", "[[Enhanced entity–relationship model]]"]
---

# Associative entity

An associative entity is a term used in  relational and entity–relationship theory. A relational database requires the implementation of a base relation (or base table) to resolve many-to-many relationships. A base relation representing this kind of entity is called, informally, an associative table.  
As mentioned above, associative entities are implemented in a database structure using associative tables, which are tables that can contain references to columns from the same or different database tables within the same database.

An associative (or junction) table maps two or more tables together by referencing the primary keys (PK) of each data table. In effect, it contains a number of foreign keys (FK), each in a many-to-one relationship from the junction table to the individual data tables. The PK of the associative table is typically composed of the FK columns themselves.
Associative tables are colloquially known under many names, including association table, bridge table, cross-reference table, crosswalk, intermediary table, intersection table, join table, junction table, link table, linking table, many-to-many resolver, map table, mapping table, pairing table, pivot table (as used in Laravel—not to be confused with the use of  pivot table in spreadsheets), or  transition table.

## Related

- [[Activity cycle diagram]]
- [[And-inverter graph]]
- [[Binary decision diagram]]
- [[C4 model]]
- [[Commutative diagram]]
- [[Concept map]]
- [[Conceptual graph]]
- [[Control-flow diagram]]
- [[Data-flow diagram]]
- [[Enhanced entity–relationship model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Associative_entity