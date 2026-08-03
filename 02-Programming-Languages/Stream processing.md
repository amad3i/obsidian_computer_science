---
title: "Stream processing"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Stream_processing"
wikipedia_categories: ["Computer architecture", "GPGPU", "Models of computation", "Programming paradigms"]
related: ["[[Dataflow]]", "[[Single instruction, multiple threads]]", "[[Abstract machine]]", "[[Abstract state machine]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Algorithm characterizations]]", "[[AMD Instinct]]", "[[Aperture (computer memory)]]"]
---

# Stream processing

In computer science, stream processing (also known as event stream processing, data stream processing, or distributed stream processing) is a programming paradigm that views streams, or sequences of events in time, as the central input and output objects of computation. Stream processing encompasses dataflow programming, reactive programming, and distributed data processing. Stream processing systems use streaming algorithms to trace parallel processing for data streams. The software stack for these systems includes components such as programming models and query languages, for expressing computation; stream management systems for distribution and scheduling; and hardware components for acceleration, including floating-point units, graphics processing units, and field-programmable gate arrays.
The stream processing paradigm simplifies parallel software and hardware by restricting the kinds of parallel computation that can be performed. Given a sequence of data (a stream), a series of operations (kernel functions) is applied to each element in the stream. Kernel functions are usually pipelined, and efficient local on-chip memory reuse is attempted in order to minimize bandwidth loss associated with external memory interaction. Uniform streaming, in which a single kernel function is applied to all elements in the stream, is typical. Because the kernel and stream abstractions expose data dependencies, compiler tools can fully automate and optimize on-chip management tasks. Stream processing hardware can use techniques such as scoreboarding to initiate direct memory access (DMA) when dependencies are resolved. The elimination of manual DMA management reduces software complexity, while the reduced reliance on hardware cached I/O decreases the memory footprint required by specialized computational units such as arithmetic logic units.
During the 1980s stream processing was explored within dataflow programming. One example is the language SISAL.

## Related

- [[Dataflow]]
- [[Single instruction, multiple threads]]
- [[Abstract machine]]
- [[Abstract state machine]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Algorithm characterizations]]
- [[AMD Instinct]]
- [[Aperture (computer memory)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stream_processing