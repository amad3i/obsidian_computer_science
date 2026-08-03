---
title: "Inductive type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Inductive_type"
wikipedia_categories: ["Type theory"]
related: ["[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]", "[[Bounded quantification]]"]
---

# Inductive type

In type theory, a system has inductive types if it has facilities for creating a new type from constants and functions that create terms of that type. The feature serves a role similar to data structures in a programming language and allows a type theory to add concepts like numbers, relations, and trees. As the name suggests, inductive types can be self-referential, but usually only in a way that permits structural recursion.
The standard example is encoding the natural numbers using Peano's encoding. It can be defined in Rocq (formerly named Coq) as follows:

Here, a natural number is created either from the constant "O" (representing zero) or by applying the function "S" to another natural number. "S" is the successor function which represents adding one to a number. Thus, "S O" is one, "S (S O)" is two, "S (S (S O))" is three, and so on.
Since their introduction, inductive types have been extended to encode more and more structures, while still being predicative and supporting structural recursion.

## Related

- [[Abstract data type]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Attribute domain]]
- [[Automath]]
- [[Axiom of reducibility]]
- [[Bottom type]]
- [[Bounded quantification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Inductive_type