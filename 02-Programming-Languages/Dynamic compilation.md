---
title: "Dynamic compilation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_compilation"
wikipedia_categories: ["Compiler construction"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Dynamic compilation

Dynamic compilation is a process used by some programming language implementations to gain performance during program execution. Although the technique originated in Smalltalk, the best-known language that uses this technique is Java. Since the machine code emitted by a dynamic compiler is constructed and optimized at program runtime, the use of dynamic compilation enables optimizations for efficiency not available to statically-compiled programs (i.e. those compiled by a so-called "batch compiler", as written below) except through code duplication or metaprogramming.
Runtime environments using dynamic compilation typically have programs run slowly for the first few minutes, and then after that, most of the compilation and recompilation is done and it runs quickly. Due to this initial performance lag, dynamic compilation is undesirable in certain cases. In most implementations of dynamic compilation, some optimizations that could be done at the initial compile time are delayed until further compilation at run-time, causing further unnecessary slowdowns. Just-in-time compilation is a form of dynamic compilation.

## Related

- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Basic block]]
- [[Binary recompiler]]
- [[Bootstrapping (compilers)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_compilation