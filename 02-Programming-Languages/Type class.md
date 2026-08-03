---
title: "Type class"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Type_class"
wikipedia_categories: ["Data types", "Functional programming", "Programming language comparisons", "Type theory"]
related: ["[[Option type]]", "[[Polymorphism (computer science)]]", "[[Algebraic data type]]", "[[Flow-sensitive typing]]", "[[Generalized algebraic data type]]", "[[Type family]]", "[[Type variable]]", "[[Abstract data type]]", "[[Anonymous function]]", "[[Any type]]"]
---

# Type class

In computer science, a type class is a type system construct that supports ad hoc polymorphism in a programming language. This is achieved by adding constraints to type variables in parametrically polymorphic types. Such a constraint typically involves a type class T and a type variable a, and means that a can only be instantiated to a type whose members support the overloaded operations associated with T.
Type classes were first implemented in the language Haskell after first being proposed by Philip Wadler and Stephen Blott as an extension to eqtypes in Standard ML, and were originally conceived as a way of implementing overloaded arithmetic and equality operators in a principled fashion.
In contrast with the "eqtypes" of Standard ML, overloading the equality operator through the use of type classes in Haskell does not need extensive modification of the compiler frontend or the underlying type system.

## Related

- [[Option type]]
- [[Polymorphism (computer science)]]
- [[Algebraic data type]]
- [[Flow-sensitive typing]]
- [[Generalized algebraic data type]]
- [[Type family]]
- [[Type variable]]
- [[Abstract data type]]
- [[Anonymous function]]
- [[Any type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Type_class