---
title: "Code generation (compiler)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Code_generation_(compiler)"
wikipedia_categories: ["Compiler construction", "Machine code"]
related: ["[[Abstract syntax]]", "[[Addressing mode]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]"]
---

# Code generation (compiler)

In computing, code generation is part of the process chain of a compiler, in which an intermediate representation of source code is converted into a form (e.g., machine code) that the target system can readily execute.
Sophisticated compilers typically perform multiple passes over various intermediate forms. This multi-stage process is used because many algorithms for code optimization are easier to apply one at a time, or because the input to one optimization relies on the completed processing performed by another optimization. This organization also facilitates the creation of a single compiler that can target multiple architectures, as only the last of the code generation stages (the backend) needs to change from target to target. (For more information on compiler design, see Compiler.)
The input to the code generator typically consists of a parse tree or an abstract syntax tree. The tree is converted into a linear sequence of instructions, usually in an intermediate language such as three-address code. Further stages of compilation may or may not be referred to as "code generation", depending on whether they involve a significant change in the representation of the program. (For example, a peephole optimization pass would not likely be called "code generation", although a code generator might incorporate a peephole optimization pass.)

## Related

- [[Abstract syntax]]
- [[Addressing mode]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Basic block]]
- [[Binary recompiler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Code_generation_(compiler)