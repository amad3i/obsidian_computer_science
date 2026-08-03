---
title: "Compile time"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Compile_time"
wikipedia_categories: ["Compiler construction"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Compile time

In computing, compile time is the period of time when a compiler processes source code into other code that is more readily executable – typically object code or byte code. Compile time is a phase in the operational life cycle of a program as it transitions from development to execution. The length of time it takes to compile is usually referred to as compilation time although compile time might also be used.
Compile time can be subdivided by the phases of a compiler. Most compilers have at least the following phases: syntax analysis, semantic analysis, and code generation. Many compilers include one or more optimization phases. For example, each constant expressions might be evaluated via compile-time execution to produce a value that results in improved runtime performance.
Properties of a program that can be determined at compile time include range-checks (e.g., proving that an array index will not exceed the array bounds), deadlock freedom in concurrent languages, or timings (e.g., proving that a sequence of code takes no more than an allocated amount of time). For statically-typed languages such as C++, Java or Rust, types are checked at compile time to ensure type safety.
Compiling is typically part of a build process (at build time). A build may also include linking (at link time). Run time is the duration when the program is running.
Often, compilation occurs as a separate step before running a program. But with dynamic compilation, transformation to machine language happens as part of the process of running it – intertwining run time and compile time. Often this is split into two distinct processes: a build-time process that converts source code to an intermediate representation (IR) and a run-time process that converts the IR to machine code.

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

- Wikipedia: https://en.wikipedia.org/wiki/Compile_time