---
title: "Very long instruction word"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Very_long_instruction_word"
wikipedia_categories: ["Digital signal processing", "Instruction processing", "Instruction set architectures", "Parallel computing", "Very long instruction word computing"]
related: ["[[Degree of parallelism]]", "[[FR-V (microprocessor)]]", "[[General-purpose computing on graphics processing units]]", "[[Instruction set architecture]]", "[[Instruction-level parallelism]]", "[[Memory-level parallelism]]", "[[Multi-core processor]]", "[[Multidimensional DSP with GPU acceleration]]", "[[Multithreading (computer architecture)]]", "[[Parallel processing (DSP implementation)]]"]
---

# Very long instruction word

Very long instruction word (VLIW) is a type of  instruction set architecture  designed to exploit  instruction-level parallelism (ILP) by explicitly specifying, in advance, which instructions execute in parallel. 
VLIW architectures contrast with superscalar architectures, the predominant approach for exploiting ILP, where hardware dynamically discovers and schedules parallel execution at runtime. VLIW's primary motivation is achieving higher performance without the hardware complexity of superscalar designs. The circuitry needed to repeatedly analyze instruction streams and schedule parallel execution at runtime increases chip area, cost, and power consumption while potentially reducing clock speeds.
The name VLIW derives from the instruction format found in almost all implementations, where the compiler bundles operations intended to execute simultaneously into a single, wide instruction word dispatched to execution units as one unit. These words can be extremely wide—implementations have used instruction words of 1 kilobit or more. But this is only a side effect of the natural way to implement a VLIW. The distinguishing feature of a VLIW is that the exact execution order and parallelism are discovered and specified in advance.
VLIW shifts the burden of identifying parallelism from hardware to the compiler. This increases compiler complexity substantially, as it must schedule instructions while ensuring correctness, resolving resource conflicts (for execution units, registers, and memory ports), and exploiting the greater parallelism that simpler VLIW hardware exposes.

## Related

- [[Degree of parallelism]]
- [[FR-V (microprocessor)]]
- [[General-purpose computing on graphics processing units]]
- [[Instruction set architecture]]
- [[Instruction-level parallelism]]
- [[Memory-level parallelism]]
- [[Multi-core processor]]
- [[Multidimensional DSP with GPU acceleration]]
- [[Multithreading (computer architecture)]]
- [[Parallel processing (DSP implementation)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Very_long_instruction_word