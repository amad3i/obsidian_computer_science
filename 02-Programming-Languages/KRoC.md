---
title: "KRoC"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/KRoC"
wikipedia_categories: ["Compilers", "University of Kent"]
related: ["[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# KRoC

The Kent Retargetable occam Compiler (KRoC), is computer software, an implementation of the programming language occam, that is based on the Inmos occam 2.1 compiler as a front-end and a retargetable back-end to produce machine code for various microprocessors. Ports of the compiler have been made for PowerPC, SPARC, x86, and Alpha processors.
Along with the translation to different processors, the KRoC team have modified the compiler significantly, creating a compiler for what has become termed occam v2.5, and now as occam-π, pronounced occam-pi.
Originally the translation from the occam compiler front-end was by interpretation of the American Standard Code for Information Interchange (ASCII) file in assembly language. This worked reasonably well but was slow and occasionally inconvenient.
The current KRoC compiler target is an Extended Transputer Code (ETC), which is then translated into the target machine language. ETC code can be viewed as a kind of byte code: it is a compact description of the compiler's intent on a virtual machine that is similar to the transputer.
ETC-code variants of the KRoC compiler exist for Intel x86 on Linux, and on Windows using Cygwin. A SPARC port was being  worked on at some point.

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

- Wikipedia: https://en.wikipedia.org/wiki/KRoC