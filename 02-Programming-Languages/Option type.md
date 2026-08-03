---
title: "Option type"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Option_type"
wikipedia_categories: ["Data types", "Functional programming", "Programming language comparisons", "Type theory"]
related: ["[[Polymorphism (computer science)]]", "[[Type class]]", "[[Algebraic data type]]", "[[Flow-sensitive typing]]", "[[Generalized algebraic data type]]", "[[Type family]]", "[[Type variable]]", "[[Abstract data type]]", "[[Anonymous function]]", "[[Any type]]"]
---

# Option type

In programming languages (especially functional programming languages) and type theory, an option type or maybe type is a polymorphic type that represents encapsulation of an optional value; e.g., it is used as the return type of functions which may or may not return a meaningful value when they are applied. It consists of a constructor which either is empty (often named None or Nothing), or which encapsulates the original data type A (often written Just A or Some A).
A distinct, but related concept outside of functional programming, which is popular in object-oriented programming, is called nullable types (often expressed as A?). The core difference between option types and nullable types is that option types support nesting (e.g. Maybe (Maybe String) ≠ Maybe String), while nullable types do not (e.g. String?? = String?).

## Related

- [[Polymorphism (computer science)]]
- [[Type class]]
- [[Algebraic data type]]
- [[Flow-sensitive typing]]
- [[Generalized algebraic data type]]
- [[Type family]]
- [[Type variable]]
- [[Abstract data type]]
- [[Anonymous function]]
- [[Any type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Option_type