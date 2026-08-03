---
title: "Gather/scatter (vector addressing)"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Gather/scatter_(vector_addressing)"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Gather/scatter (vector addressing)

Gather/scatter is a type of memory addressing that at once collects (gathers) from, or stores (scatters) data to, multiple arbitrary memory indices. Examples of its use include sparse linear algebra operations, sorting algorithms, fast Fourier transforms, and some computational graph theory problems. It is the vector equivalent of register indirect addressing, with gather involving indexed reads, and scatter, indexed writes. Vector processors (and some SIMD units in CPUs) have hardware support for gather and scatter operations, as do many input/output systems, allowing large data sets to be transferred to main memory more rapidly.
The concept is somewhat similar to vectored I/O, which is sometimes also referred to as scatter-gather I/O. This system differs in that it is used to map multiple sources of data from contiguous structures into a single stream for reading or writing. A common example is writing out a series of strings, which in most programming languages would be stored in separate memory locations.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gather/scatter_(vector_addressing)