---
title: "Type family"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Type_family"
wikipedia_categories: ["Data types", "Functional programming", "Type theory"]
related: ["[[Algebraic data type]]", "[[Generalized algebraic data type]]", "[[Option type]]", "[[Polymorphism (computer science)]]", "[[Type class]]", "[[Abstract data type]]", "[[Anonymous function]]", "[[Any type]]", "[[Bottom type]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]"]
---

# Type family

In computer science, a type family associates data types with other data types, using a type-level function defined by an open-ended collection of valid instances of input types and the corresponding output types.
Type families are a feature of some type systems that allow partial functions between types to be defined by pattern matching. This is in contrast to data type constructors, which define injective functions from all types of a particular kind to a new set of types, and type synonyms (a.k.a. typedef), which define functions from all types of a particular kind to another existing set of types using a single case.
Type families and type classes are closely related: normal type classes define partial functions from types to a collection of named values by pattern matching on the input types, while type families define partial functions from types to types by pattern matching on the input types. In fact, in many uses of type families there is a single type class which logically contains both values and types associated with each instance. A type family declared inside a type class is called an associated type.
Programming languages with support for type families or similar features include Haskell (with a common language extension), Standard ML (through its module system), Rust, Scala (under the name "abstract types"), and C++ (through use of typedefs in templates).

## Related

- [[Algebraic data type]]
- [[Generalized algebraic data type]]
- [[Option type]]
- [[Polymorphism (computer science)]]
- [[Type class]]
- [[Abstract data type]]
- [[Anonymous function]]
- [[Any type]]
- [[Bottom type]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Type_family