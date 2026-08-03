---
title: "Aspect weaver"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Aspect_weaver"
wikipedia_categories: ["Aspect-oriented programming", "Aspect-oriented software development", "Compiler construction", "Programming language implementation"]
related: ["[[Aspect-oriented programming]]", "[[AspectJ]]", "[[Funarg problem]]", "[[Lexical analysis]]", "[[Object file]]", "[[Optimizing compiler]]", "[[bss]]", "[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]"]
---

# Aspect weaver

An aspect weaver is a metaprogramming utility for aspect-oriented languages designed to take instructions specified by aspects (isolated representations of significant concepts in a program) and generate the final implementation code. The weaver integrates aspects into the locations specified by the software as a pre-compilation step. By merging aspects and classes (representations of the structure of entities in the program), the weaver generates a woven class.
Aspect weavers take instructions known as advice specified through the use of pointcuts and join points, special segments of code that indicate what methods should be handled by aspect code. The implementation of the aspect then specifies whether the related code should be added before, after, or throughout the related methods. By doing this, aspect weavers improve modularity, keeping code in one place that would otherwise have been interspersed throughout various, unrelated classes.

## Related

- [[Aspect-oriented programming]]
- [[AspectJ]]
- [[Funarg problem]]
- [[Lexical analysis]]
- [[Object file]]
- [[Optimizing compiler]]
- [[bss]]
- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Aspect_weaver