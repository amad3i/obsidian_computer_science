---
title: "Slot (computer architecture)"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Slot_(computer_architecture)"
wikipedia_categories: ["Computer architecture", "Computing stubs"]
related: ["[[Data memory-dependent prefetcher]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Auditory display]]", "[[Automatic system recovery]]", "[[Autonomous decentralized system]]"]
---

# Slot (computer architecture)

A slot comprises the operation issue and data path machinery surrounding a set of one or more execution unit (also called a functional unit (FU)) which share these resources. The term slot is common for this purpose in very long instruction word (VLIW) computers, where the relationship between operation in an instruction and pipeline to execute it is explicit. In dynamically scheduled machines, the concept is more commonly called an execute pipeline.
Modern conventional central processing units (CPU) have several compute pipelines, for example: two arithmetic logic units (ALU), one floating point unit (FPU), one Streaming SIMD Extensions (SSE) (such as MMX), one branch. Each of them can issue one instruction per basic instruction cycle, but can have several instructions in process. These are what correspond to slots. The pipelines may have several FUs, such as an adder and a multiplier, but only one FU in a pipeline can be issued to in a given cycle. The FU population of a pipeline (slot) is a design option in a CPU.

## Related

- [[Data memory-dependent prefetcher]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Auditory display]]
- [[Automatic system recovery]]
- [[Autonomous decentralized system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Slot_(computer_architecture)