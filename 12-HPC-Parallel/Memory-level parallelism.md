---
title: "Memory-level parallelism"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Memory-level_parallelism"
wikipedia_categories: ["Instruction processing", "Parallel computing"]
related: ["[[Degree of parallelism]]", "[[General-purpose computing on graphics processing units]]", "[[Instruction-level parallelism]]", "[[Multithreading (computer architecture)]]", "[[Speculative multithreading]]", "[[Very long instruction word]]", "[[Wide-issue]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]"]
---

# Memory-level parallelism

In computer architecture, memory-level parallelism (MLP) is the ability to have pending multiple memory operations, in particular cache misses or translation lookaside buffer (TLB) misses, at the same time.
In a single processor, MLP may be considered a form of instruction-level parallelism (ILP). However, ILP is often conflated with superscalar, the ability to execute more than one instruction at the same time, e.g. a processor such as the Intel Pentium Pro is five-way superscalar, with the ability to start executing five different microinstructions in a given cycle, but it can handle four different cache misses for up to 20 different load microinstructions at any time.
It is possible to have a machine that is not superscalar but which nevertheless has high MLP. 
Arguably a machine that has no ILP, which is not superscalar, which executes one instruction at a time in a non-pipelined manner, but which performs hardware prefetching (not software instruction-level prefetching) exhibits MLP (due to multiple prefetches outstanding) but not ILP. This is because there are multiple memory operations outstanding, but not instructions. Instructions are often conflated with operations.
Furthermore, multiprocessor and multithreaded computer systems may be said to exhibit MLP and ILP due to parallelism—but not intra-thread, single process, ILP and MLP. Often, however, we restrict the terms MLP and ILP to refer to extracting such parallelism from what appears to be non-parallel single threaded code.

## Related

- [[Degree of parallelism]]
- [[General-purpose computing on graphics processing units]]
- [[Instruction-level parallelism]]
- [[Multithreading (computer architecture)]]
- [[Speculative multithreading]]
- [[Very long instruction word]]
- [[Wide-issue]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Memory-level_parallelism