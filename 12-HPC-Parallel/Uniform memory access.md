---
title: "Uniform memory access"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Uniform_memory_access"
wikipedia_categories: ["Computer memory", "Parallel computing"]
related: ["[[Cache-only memory architecture]]", "[[Content-addressable parallel processor]]", "[[MCDRAM]]", "[[Memory coherence]]", "[[Non-uniform memory access]]", "[[2025–present global memory supply shortage]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]"]
---

# Uniform memory access

Uniform memory access (UMA) is a shared-memory architecture used in parallel computers. All processors in the UMA model share their physical memory uniformly. In an UMA architecture, access time to a memory location is independent of which processor makes the request, or which memory chip contains the transferred data. Uniform memory access computer architectures are often contrasted with non-uniform memory access (NUMA) architectures. In the NUMA architecture, each processor may use a private cache. Peripherals are also shared in some fashion. The UMA model is suitable for general purpose and time sharing applications by multiple users. It can be used to speed up the execution of a single large program in time-critical applications.

## Related

- [[Cache-only memory architecture]]
- [[Content-addressable parallel processor]]
- [[MCDRAM]]
- [[Memory coherence]]
- [[Non-uniform memory access]]
- [[2025–present global memory supply shortage]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Uniform_memory_access