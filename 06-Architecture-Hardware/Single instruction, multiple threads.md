---
title: "Single instruction, multiple threads"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Single_instruction,_multiple_threads"
wikipedia_categories: ["Classes of computers", "Computer architecture", "GPGPU", "Parallel computing", "SIMD computing", "Threads (computing)"]
related: ["[[Cellular architecture]]", "[[Single instruction, multiple data]]", "[[Spatial architecture]]", "[[Superscalar processor]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Asymmetric multiprocessing]]", "[[Automatic vectorization]]", "[[Computer cluster]]", "[[CUDA]]"]
---

# Single instruction, multiple threads

Single instruction, multiple threads (SIMT) is an execution model used in parallel computing where a single central "control unit" broadcasts an instruction to multiple "processing units" for them to all optionally perform simultaneous synchronous and fully-independent parallel execution of that one instruction. Each PU has its own independent data and address registers, its own independent memory, but no PU in the array has a program counter. In Flynn's 1972 taxonomy this arrangement is a variation of SIMD termed an array processor.

 
The SIMT execution model has been implemented on several GPUs and is relevant for general-purpose computing on graphics processing units (GPGPU), e.g. some supercomputers combine CPUs with GPUs: in the ILLIAC IV that CPU was a Burroughs B6500.
The SIMT execution model is still only a way to present to the programmer what is fundamentally still a predicated SIMD concept. Programs must be designed with predicated SIMD in mind. With instruction issue (as a synchronous broadcast) being handled by the single control unit, SIMT cannot by design allow threads (PEs, lanes) to diverge by branching, because only the control unit has a program counter. If possible, therefore, branching is to be avoided.

## Related

- [[Cellular architecture]]
- [[Single instruction, multiple data]]
- [[Spatial architecture]]
- [[Superscalar processor]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Asymmetric multiprocessing]]
- [[Automatic vectorization]]
- [[Computer cluster]]
- [[CUDA]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Single_instruction,_multiple_threads