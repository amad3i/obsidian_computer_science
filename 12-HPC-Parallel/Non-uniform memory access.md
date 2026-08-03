---
title: "Non-uniform memory access"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Non-uniform_memory_access"
wikipedia_categories: ["Computer memory", "Parallel computing"]
related: ["[[Cache-only memory architecture]]", "[[Content-addressable parallel processor]]", "[[MCDRAM]]", "[[Memory coherence]]", "[[Uniform memory access]]", "[[2025–present global memory supply shortage]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]"]
---

# Non-uniform memory access

Non-uniform memory access (NUMA) is a computer memory design used in multiprocessing, where the memory access time depends on the memory location relative to the processor. Under NUMA, a processor can access its own local memory faster than non-local memory (memory local to another processor or memory shared between processors). NUMA is beneficial for workloads with high memory locality of reference and low lock contention, because a processor may operate on a subset of memory mostly or entirely within its own cache node, reducing traffic on the memory bus.
NUMA architectures logically follow in scaling from symmetric multiprocessing (SMP) architectures. They were developed commercially during the 1990s by Unisys, Convex Computer (later Hewlett-Packard), Honeywell Information Systems Italy (HISI) (later Groupe Bull), Silicon Graphics (later Silicon Graphics International), Sequent Computer Systems (later IBM), Data General (later EMC, now Dell Technologies), Digital (later Compaq, then HP, now HPE) and ICL. Techniques developed by these companies later featured in a variety of Unix-like operating systems, and to an extent in Windows NT.
The first commercial implementation of a NUMA-based Unix system was the Symmetrical Multi Processing XPS-100 family of servers, designed by Dan Gielan of VAST Corporation for Honeywell Information Systems Italy.

## Related

- [[Cache-only memory architecture]]
- [[Content-addressable parallel processor]]
- [[MCDRAM]]
- [[Memory coherence]]
- [[Uniform memory access]]
- [[2025–present global memory supply shortage]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Non-uniform_memory_access