---
title: "Attribute domain"
tags: ["cs", "data-databases", "advanced"]
domain: Data & Databases
level: advanced
source: "https://en.wikipedia.org/wiki/Attribute_domain"
wikipedia_categories: ["Database theory", "Type theory"]
related: ["[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bidirectionalization]]", "[[Bottom type]]", "[[Bounded quantification]]"]
---

# Attribute domain

In computing, the attribute domain is the set of values allowed in an attribute.
For example: 

Rooms in hotel (1–300)
Age (1–99)
Married (yes or no)
Nationality (Nepalese, Indian, American, or British)
Colors (Red, Yellow, Green)

For the relational model it is a requirement that each part of a tuple be atomic. The consequence is that each value in the tuple must be of some basic type, like a string or an integer. For the elementary type to be atomic it cannot be broken into more pieces. Alas, the domain is an elementary type, and attribute domain the domain a given attribute belongs to an abstraction belonging to or characteristic of an entity.
For example, in SQL, one can create their own domain for an attribute with the command

The above command says: "Create a datatype SSN_TYPE that is of character type with size 9".

## Related

- [[Abstract data type]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Automath]]
- [[Axiom of reducibility]]
- [[Bidirectionalization]]
- [[Bottom type]]
- [[Bounded quantification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Attribute_domain