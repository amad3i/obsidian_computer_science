---
title: "One-to-many (data model)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/One-to-many_(data_model)"
wikipedia_categories: ["Data modeling", "Systems theory stubs"]
related: ["[[One-to-one (data model)]]", "[[Activity cycle diagram]]", "[[Allopoiesis]]", "[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Bitemporal modeling]]", "[[Building information modeling]]", "[[BuildingSMART Data Dictionary]]"]
---

# One-to-many (data model)

In systems analysis, a one-to-many relationship is a type of cardinality that refers to the relationship between two entities (see also entity–relationship model). For example, take a car and an owner of the car. The car can only be owned by one owner at a time or not owned at all, and an owner could own zero, one, or multiple cars. One owner could have many cars, one-to-many.
In a relational database, a one-to-many relationship exists when one record is related to many records of another table. A one-to-many relationship is not a property of the data, but rather of the relationship itself. One-to-many often refer to a primary key to foreign key relationship between two tables, where the record in the first table can relate to multiple records in the second table. A foreign key is one side of the relationship that shows a row or multiple rows, with one of those rows being the primary key already listed on the first table. This is also called a foreign key constraint, which is important to keep data from being duplicated and have relationships within the database stay reliable as more information is added.
Many-to-many relationships are not able to be used in relational databases and must be converted to one-to-many relationships. Both one-to-many and one-to-one relationships are common in relational databases.
The opposite of one-to-many is many-to-one. The transpose of a one-to-many relationship is a many-to-one relationship.

## Related

- [[One-to-one (data model)]]
- [[Activity cycle diagram]]
- [[Allopoiesis]]
- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]
- [[BIM Collaboration Format]]
- [[Bitemporal modeling]]
- [[Building information modeling]]
- [[BuildingSMART Data Dictionary]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/One-to-many_(data_model)