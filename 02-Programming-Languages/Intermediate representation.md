---
title: "Intermediate representation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Intermediate_representation"
wikipedia_categories: ["Compiler construction", "Programming language classification"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Architecture description language]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]"]
---

# Intermediate representation

An intermediate representation (IR) is the data structure or code used internally by a compiler or virtual machine to represent source code. An IR is designed to be conducive to further processing, such as optimization and translation. A "good" IR must be accurate – capable of representing the source code without loss of information – and independent of any particular source or target language. An IR may take one of several forms: an in-memory data structure, or a special tuple- or stack-based code readable by the program. In the latter case it is also called an intermediate language.
A canonical example is found in most modern compilers. For example, the CPython interpreter transforms the linear human-readable text representing a program into an intermediate graph structure that allows flow analysis and re-arrangement before execution. Use of an intermediate representation such as this allows compiler systems like the GNU Compiler Collection and LLVM to be used by many different source languages to generate code for many different target architectures.

## Related

- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Architecture description language]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Basic block]]
- [[Binary recompiler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Intermediate_representation