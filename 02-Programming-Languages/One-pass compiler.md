---
title: "One-pass compiler"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/One-pass_compiler"
wikipedia_categories: ["Compilers"]
related: ["[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# One-pass compiler

In computer programming, a one-pass compiler is a compiler that processes each compilation unit only once, sequentially translating each source statement or declaration into something close to its final machine code.  This is in contrast to a multi-pass compiler which converts the program into one or more intermediate representations in steps between source code and machine code, and which reprocesses the entire compilation unit in each sequential pass.
A one-pass compiler initially has to leave addresses for forward jumps unresolved. These can be handled in various ways (e.g. tables of forward jumps and targets) without needing to have another complete pass. Some nominally one-pass compilers effectively 'pass the buck' by generating assembly language and letting the assembler sort out the forward references, but this requires one or more passes in the assembler.
One-pass compilers are smaller and faster than multi-pass compilers.
One-pass compilers are unable to generate as efficient programs as multi-pass compilers due to the limited scope of available information. Many effective compiler optimizations require multiple passes over a basic block, loop (especially nested loops), subroutine, or entire module.  Some require passes over an entire program.

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

- Wikipedia: https://en.wikipedia.org/wiki/One-pass_compiler