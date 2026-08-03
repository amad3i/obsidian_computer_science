---
title: "Multidimensional DSP with GPU acceleration"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multidimensional_DSP_with_GPU_acceleration"
wikipedia_categories: ["Digital signal processing", "Digital signal processors", "GPGPU", "Parallel computing"]
related: ["[[AMD Instinct]]", "[[Asynchronous array of simple processors]]", "[[CUDA]]", "[[Digital signal controller]]", "[[Digital signal processor]]", "[[FR-V (microprocessor)]]", "[[General-purpose computing on graphics processing units]]", "[[Graphics Core Next]]", "[[IWOCL]]", "[[Media processor]]"]
---

# Multidimensional DSP with GPU acceleration

Multidimensional digital signal processing (MDSP) refers to the extension of digital signal processing (DSP) techniques to signals that vary in more than one dimension. While conventional DSP typically deals with one-dimensional data, such as time-varying audio signals, MDSP involves processing signals in two or more dimensions. Many of the principles from one-dimensional DSP, such as Fourier transforms and filter design, have analogous counterparts in multidimensional signal processing.
Modern general-purpose computing on graphics processing units (GPGPUs) have an excellent throughput on vector operations and numeric manipulations through a high degree of parallel computations. Processing digital signals, particularly multidimensional signals, often involves a series of vector operations on massive numbers of independent data samples, GPGPUs are now widely employed to accelerate multidimensional DSP, such as image processing, video codecs, radar signal analysis, sonar signal processing, and ultrasound scanning. Conceptually, GPGPUs dramatically reduce the computation complexity when compared with central processing units (CPUs), digital signal processors (DSPs), or other FPGA accelerators.

## Related

- [[AMD Instinct]]
- [[Asynchronous array of simple processors]]
- [[CUDA]]
- [[Digital signal controller]]
- [[Digital signal processor]]
- [[FR-V (microprocessor)]]
- [[General-purpose computing on graphics processing units]]
- [[Graphics Core Next]]
- [[IWOCL]]
- [[Media processor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multidimensional_DSP_with_GPU_acceleration