---
title: "General-purpose computing on graphics processing units"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units"
wikipedia_categories: ["GPGPU", "Graphics cards", "Graphics hardware", "Instruction processing", "Parallel computing", "Video game development"]
related: ["[[CUDA]]", "[[Nvidia Tesla]]", "[[ROCm]]", "[[Tesla (microarchitecture)]]", "[[AMD Instinct]]", "[[Degree of parallelism]]", "[[Graphics Core Next]]", "[[Instruction-level parallelism]]", "[[IWOCL]]", "[[List of home computers by video hardware]]"]
---

# General-purpose computing on graphics processing units

General-purpose computing on graphics processing units (GPGPU, or less often GPGP) is the use of a graphics processing unit (GPU), which typically handles computation only for computer graphics, to perform computation in applications traditionally handled by the central processing unit (CPU). The use of multiple video cards in one computer, or large numbers of graphics chips, further parallelizes the already parallel nature of graphics processing.
Essentially, a GPGPU pipeline is a kind of parallel processing between one or more GPUs and CPUs, with special accelerated instructions for processing image or other graphic forms of data. While GPUs operate at lower frequencies, they typically have many times the number of processing elements. Thus, GPUs can process far more pictures and other graphical data per second than a traditional CPU. Migrating data into parallel form and then using the GPU to process it can (theoretically) create a large speedup.
GPGPU pipelines were developed at the beginning of the 21st century for graphics processing (e.g. for better shaders). From the history of supercomputing it is well-known that scientific computing drives the largest concentrations of Computing power in history, listed in the TOP500: the majority today utilize GPUs.
The best-known GPGPUs are Nvidia Tesla that are used for Nvidia DGX, alongside AMD Instinct and Intel Gaudi.

## Related

- [[CUDA]]
- [[Nvidia Tesla]]
- [[ROCm]]
- [[Tesla (microarchitecture)]]
- [[AMD Instinct]]
- [[Degree of parallelism]]
- [[Graphics Core Next]]
- [[Instruction-level parallelism]]
- [[IWOCL]]
- [[List of home computers by video hardware]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units