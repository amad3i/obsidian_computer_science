---
title: "Molecular modeling on GPUs"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Molecular_modeling_on_GPUs"
wikipedia_categories: ["Chemistry software", "Computational chemistry", "GPGPU", "Molecular dynamics", "Molecular modelling"]
related: ["[[Accessible surface area]]", "[[Combining rules]]", "[[Implicit solvation]]", "[[Molecular dynamics]]", "[[Shifted force method]]", "[[Adaptive sampling]]", "[[Car–Parrinello molecular dynamics]]", "[[Cell lists]]", "[[Constraint (computational chemistry)]]", "[[Docking (molecular)]]"]
---

# Molecular modeling on GPUs

Molecular modeling on GPU is the technique of using a graphics processing unit (GPU) for molecular simulations.
In 2007, Nvidia introduced video cards that could be used not only to show graphics but also for scientific calculations. These cards include many arithmetic units (as of 2022, up to 18,176 in the RTX 6000 Ada) working in parallel. Long before this event, the computational power of video cards was purely used to accelerate graphics calculations. The new features of these cards made it possible to develop parallel programs in a high-level application programming interface (API) named CUDA. This technology  substantially simplified programming by enabling programs to be written in C/C++. More recently, OpenCL allows cross-platform GPU acceleration.
Quantum chemistry calculations and molecular mechanics simulations (molecular modeling in terms of classical mechanics) are among beneficial applications of this technology. The video cards can accelerate the calculations tens of times, so a PC with such a card has the power similar to that of a cluster of workstations based on common processors.

## Related

- [[Accessible surface area]]
- [[Combining rules]]
- [[Implicit solvation]]
- [[Molecular dynamics]]
- [[Shifted force method]]
- [[Adaptive sampling]]
- [[Car–Parrinello molecular dynamics]]
- [[Cell lists]]
- [[Constraint (computational chemistry)]]
- [[Docking (molecular)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Molecular_modeling_on_GPUs