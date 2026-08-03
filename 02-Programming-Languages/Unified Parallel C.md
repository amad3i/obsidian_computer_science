---
title: "Unified Parallel C"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Unified_Parallel_C"
wikipedia_categories: ["C programming language family", "Concurrent programming languages", "Parallel computing"]
related: ["[[Alef (programming language)]]", "[[Algorithmic skeleton]]", "[[Chapel (programming language)]]", "[[Cilk]]", "[[Concurrent Collections]]", "[[Concurrent logic programming]]", "[[Dart (programming language)]]", "[[Flow-based programming]]", "[[Go (programming language)]]", "[[Intel Parallel Building Blocks]]"]
---

# Unified Parallel C

Unified Parallel C (UPC) is an extension of the C programming language designed for high-performance computing on large-scale parallel machines, including those with a common global address space (SMP and NUMA) and those with distributed memory (e.g. clusters). The programmer is presented with a single partitioned global address space, where shared variables may be directly read and written by any processor, but each variable is physically associated with a single processor. UPC uses a single program, multiple data (SPMD) model of computation in which the amount of parallelism is fixed at program startup time, typically with a single thread of execution per processor.
In order to express parallelism, UPC extends ISO C 99 with the following constructs:

An explicitly parallel execution model
A shared address space (shared storage qualifier) with thread-local parts (normal variables)
Synchronization primitives and a memory consistency model
Explicit communication primitives, e.g. upc_memput
Memory management primitives
The UPC language evolved from experiences with three other earlier languages that proposed parallel extensions to ISO C 99: AC, Split-C, and Parallel C preprocessor (PCP). UPC is not a superset of these three languages, but rather an attempt to distill the best characteristics of each. UPC combines the programmability advantages of the shared memory programming paradigm and the control over data layout and performance of the message passing programming paradigm.

## Related

- [[Alef (programming language)]]
- [[Algorithmic skeleton]]
- [[Chapel (programming language)]]
- [[Cilk]]
- [[Concurrent Collections]]
- [[Concurrent logic programming]]
- [[Dart (programming language)]]
- [[Flow-based programming]]
- [[Go (programming language)]]
- [[Intel Parallel Building Blocks]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unified_Parallel_C