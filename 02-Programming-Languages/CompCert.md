---
title: "CompCert"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/CompCert"
wikipedia_categories: ["Compilers", "Computer programming tool stubs", "Formal methods", "Logic in computer science", "Software using the GNU Lesser General Public License"]
related: ["[[1-in-3-SAT]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Assertion (software development)]]", "[[Bisimulation]]", "[[Boolean satisfiability problem]]", "[[DREAM (software)]]", "[[Formal verification]]", "[[Interference freedom]]", "[[Logic in computer science]]"]
---

# CompCert

CompCert is a formally verified optimizing compiler for a large subset of a dialect of the programming language C, named C99 and known as Clight. As of 2018, CompCert supports the processor architectures ARM, PowerPC, RISC-V, x86, and x86-64. The project, led by Xavier Leroy, began officially in 2005, funded by the French institutes Agence nationale de la recherche (ANR) and French Institute for Research in Computer Science and Automation (INRIA). The compiler is specified, programmed and proven in proof assistant software named Rocq. CompCert is to be used to program embedded systems requiring reliability. The performance of its generated code is often close to that of GNU Compiler Collection (GCC) version 3, at optimization level -O1, and always better than that of GCC with no optimizations.
Since 2015, AbsInt offers commercial licenses, provides support and maintenance, and contributes to the advancement of the tool. CompCert is released under a noncommercial license, and is therefore not free software, although some of its source files are dual-licensed with the GNU Lesser General Public License version 2.1 or later or are available under the terms of other licenses.
For the development of CompCert, the first practically useful optimizing compiler targeting multiple commercial architectures that has a complete, mechanically checked proof of its correctness, Xavier Leroy and the development team of CompCert received the 2021 ACM Software System Award.

## Related

- [[1-in-3-SAT]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Assertion (software development)]]
- [[Bisimulation]]
- [[Boolean satisfiability problem]]
- [[DREAM (software)]]
- [[Formal verification]]
- [[Interference freedom]]
- [[Logic in computer science]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CompCert