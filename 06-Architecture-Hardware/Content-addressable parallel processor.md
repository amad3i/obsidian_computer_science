---
title: "Content-addressable parallel processor"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Content-addressable_parallel_processor"
wikipedia_categories: ["Associative arrays", "Computer hardware stubs", "Computer memory", "One-of-a-kind computers", "Parallel computing"]
related: ["[[Cache-only memory architecture]]", "[[Cellular architecture]]", "[[Finite element machine]]", "[[ILLIAC IV]]", "[[Locale (computer hardware)]]", "[[MCDRAM]]", "[[Memory coherence]]", "[[Non-uniform memory access]]", "[[Ultracomputer]]", "[[Uniform memory access]]"]
---

# Content-addressable parallel processor

A content-addressable parallel processor (CAPP) a.k.a. in Flynn's 1972 taxonomy as an associative processor is a type of parallel processor which uses content-addressing memory (CAM) principles. CAPPs are intended for bulk computation. The syntactic structure of their computing algorithm are simple, whereas the number of concurrent processes may be very large, only limited by the number of locations in the CAM. The best-known CAPP may be STARAN, completed in 1972; several similar systems were later built in other countries.
A CAPP is distinctly different from a Von Neumann architecture or classical computer that stores data in cells addressed individually by numeric address. The CAPP executes a stream of instructions that address memory based on the content (stored values) of the memory cells.  As a parallel processor, it acts on all of the cells containing that content at once. The content of all matching cells can be changed simultaneously.
A typical CAPP might consist of an array of content-addressable memory of fixed word length, a sequential instruction store, and a general purpose computer of the Von Neumann architecture that is used to interface peripherals.

## Related

- [[Cache-only memory architecture]]
- [[Cellular architecture]]
- [[Finite element machine]]
- [[ILLIAC IV]]
- [[Locale (computer hardware)]]
- [[MCDRAM]]
- [[Memory coherence]]
- [[Non-uniform memory access]]
- [[Ultracomputer]]
- [[Uniform memory access]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Content-addressable_parallel_processor