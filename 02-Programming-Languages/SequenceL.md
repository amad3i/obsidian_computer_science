---
title: "SequenceL"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/SequenceL"
wikipedia_categories: ["Array programming languages", "Concurrent programming languages", "Cross-platform software", "Declarative programming languages", "Functional languages", "Functional programming"]
related: ["[[Erlang (programming language)]]", "[[Julia (programming language)]]", "[[NESL]]", "[[Nim (programming language)]]", "[[V (programming language)]]", "[[Wolfram Language]]", "[[-Lisp]]", "[[AgentSheets]]", "[[APL (programming language)]]", "[[Atom (programming language)]]"]
---

# SequenceL

SequenceL is a general purpose functional programming language and auto-parallelizing (parallel computing) compiler and tool set, which main design objectives are performance on multi-core processor hardware, ease of programming, platform portability/optimization, and code clarity and readability. Its main advantage is that it can be used to write straightforward code that automatically exploits fully all processing power available, without programmers needing to identify parallelisms, specify vectorization, avoid race conditions, and other challenges of manual directive-based programming methods such as OpenMP.
Programs written in SequenceL can be compiled to multithreaded code that runs in parallel, with no explicit indications from a programmer of how or what to parallelize. As of 2015, versions of the SequenceL compiler generate parallel code as an intermediate representation in C++ or OpenCL, which allows it to work with most popular programming languages, including C, C++, C#, Fortran, Java, and Python. A platform-specific runtime manages the threads safely, automatically providing parallel performance according to the number of cores available. Supported instruction set architectures include ARM, x86, and POWER8.

## Related

- [[Erlang (programming language)]]
- [[Julia (programming language)]]
- [[NESL]]
- [[Nim (programming language)]]
- [[V (programming language)]]
- [[Wolfram Language]]
- [[-Lisp]]
- [[AgentSheets]]
- [[APL (programming language)]]
- [[Atom (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SequenceL