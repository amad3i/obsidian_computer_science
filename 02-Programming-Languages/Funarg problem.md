---
title: "Funarg problem"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Funarg_problem"
wikipedia_categories: ["Compiler construction", "Programming language implementation"]
related: ["[[Aspect weaver]]", "[[Lexical analysis]]", "[[Object file]]", "[[Optimizing compiler]]", "[[bss]]", "[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Assembly language]]"]
---

# Funarg problem

In computer science, the funarg problem (function argument problem) refers to the difficulty in implementing first-class functions (functions as first-class objects) in programming language implementations so as to use stack-based memory allocation of the functions.
The difficulty only arises if the body of a nested function refers directly (i.e., not by argument passing) to identifiers defined in the environment in which the function is defined, but not in the environment of the function call. A standard resolution is either to forbid such references or to create closures.
There are two subtly different versions of the funarg problem. The upwards funarg problem arises from returning (or otherwise transmitting "upwards") a function from a function call. The downwards funarg problem arises from passing a function as a parameter to another function call.

## Related

- [[Aspect weaver]]
- [[Lexical analysis]]
- [[Object file]]
- [[Optimizing compiler]]
- [[bss]]
- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Assembly language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Funarg_problem