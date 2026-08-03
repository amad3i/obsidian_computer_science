---
title: "One-to-one (data model)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/One-to-one_(data_model)"
wikipedia_categories: ["Data modeling", "Systems theory stubs"]
related: ["[[One-to-many (data model)]]", "[[Activity cycle diagram]]", "[[Allopoiesis]]", "[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[BIM Collaboration Format]]", "[[Bitemporal modeling]]", "[[Building information modeling]]", "[[BuildingSMART Data Dictionary]]"]
---

# One-to-one (data model)

In systems analysis, a one-to-one relationship is a type of cardinality that refers to the relationship between two entities (see also entity–relationship model) A and B in which one element of A may only be linked to one element of B, and vice versa. In mathematical terms, there exists a bijective function from A to B.
For instance, think of A as the set of all human beings, and B as the set of all their brains. Any person from A can and must have only one brain from B, and any human brain in B can and must belong to only one person that is contained in A.
In a relational database, a one-to-one relationship exists when one row in a table may be linked with only one row in another table and vice versa. A one-to-one relationship is not a property of the data, but rather of the relationship itself. A list of mothers and their children may happen to describe mothers with only one child, in which case one row of the mothers table will refer to only one row of the children table and vice versa. The real-world relationship that the data models is not one-to-one, because mothers may have more than one child, thus forming a one-to-many relationship. Additionally mother needs a specific definition, as a child may have more than one mother if step, adoptive, or other relationships are included resulting in a many-to-many designation.

## Related

- [[One-to-many (data model)]]
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

- Wikipedia: https://en.wikipedia.org/wiki/One-to-one_(data_model)