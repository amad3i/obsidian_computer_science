---
title: "Multi-pass compiler"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Multi-pass_compiler"
wikipedia_categories: ["Compilers"]
related: ["[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Multi-pass compiler

A multi-pass compiler is a type of compiler that processes the source code or abstract syntax tree of a program several times. This is in contrast to a one-pass compiler, which traverses the program only once. Each pass takes the result of the previous pass as the input, and creates an intermediate output. In this way, the (intermediate) code is improved pass by pass, until the final pass produces the final code.
Multi-pass compilers are sometimes called wide compilers, referring to the greater scope of the passes: they can "see" the entire program being compiled, instead of just a small portion of it. The wider scope thus available to these compilers allows better code generation (e.g. smaller code size, faster code) compared to the output of one-pass compilers, at the cost of higher compiler time and memory consumption. In addition, some languages cannot be compiled in a single pass, as a result of their design.

## Related

- [[Absoft]]
- [[Accelerated Linear Algebra]]
- [[Ahead-of-time compilation]]
- [[Apple Dylan]]
- [[Arden2ByteCode]]
- [[Ark Compiler]]
- [[Banerjee test]]
- [[Binary optimizer]]
- [[Binary recompiler]]
- [[Bootstrapping (compilers)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multi-pass_compiler