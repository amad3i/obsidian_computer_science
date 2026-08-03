---
title: "Uniqueness type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Uniqueness_type"
wikipedia_categories: ["Type theory"]
related: ["[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]", "[[Bounded quantification]]"]
---

# Uniqueness type

In computing, a unique type guarantees that an object is used in a single-threaded way, with at most a single reference to it. If a value has a unique type, a function applied to it can be optimized to update the value in-place in the object code. Such in-place updates improve the efficiency of functional languages while maintaining referential transparency. Unique types can also be used to integrate functional and imperative programming.

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

- Wikipedia: https://en.wikipedia.org/wiki/Uniqueness_type