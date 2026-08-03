---
title: "Spatial architecture"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Spatial_architecture"
wikipedia_categories: ["Classes of computers", "Computer architecture", "Hardware acceleration", "Manycore processors", "Parallel computing"]
related: ["[[Cellular architecture]]", "[[Dataflow architecture]]", "[[Manycore processor]]", "[[Single instruction, multiple threads]]", "[[Superscalar processor]]", "[[Amorphous computing]]", "[[Asymmetric multiprocessing]]", "[[Asynchronous array of simple processors]]", "[[Computer cluster]]", "[[DOPIPE]]"]
---

# Spatial architecture

In computer science, spatial architectures are a kind of computer architecture leveraging many collectively coordinated and directly communicating processing elements (PEs) to quickly and efficiently run highly parallelizable kernels.
The "spatial" term comes from processing element instances being typically arranged in an array or grid, both logically and in the silicon design.
Their most common workloads consist of matrix multiplications, convolutions, or, in general, tensor contractions.
As such, spatial architectures are often used in AI accelerators.
The key goal of a spatial architecture is to reduce the latency and power consumption of running very large kernels through the exploitation of scalable parallelism and data reuse.
Consider a kernel, i.e. a function to be applied to several inputs, expressed as one or more loops; this means distributing its computations between processing elements while ensuring that their data dependencies land either within the same element or the same region of elements.
While spatial architectures can be designed or programmed to support different algorithms, each workload must then be mapped onto the processing elements using specialized dataflows.
Formulating a mapping involves the assignment of each operation to a processing element and the scheduling of the ensuing data movements.
All tuned to maximize data parallelism and reuse.
Spatial architectures are classifiable as a SPMD (or single function multiple data) array processor, in that each processing element runs the same operations on a different subset of data, yet they are still programmed through a single mapping.
The architecture of an individual processing element can then itself belong to any Flynn class.
In particular, spatial architectures are well suited for applications whose dataflow exhibits producer-consumer relationships (e.g., parallel reduce) or can leverage efficient data sharing among a region of PEs.
Spatial architectures can typically be found as hardware accelerators in heterogeneous systems, under the broader category of manycore processor.

## Related

- [[Cellular architecture]]
- [[Dataflow architecture]]
- [[Manycore processor]]
- [[Single instruction, multiple threads]]
- [[Superscalar processor]]
- [[Amorphous computing]]
- [[Asymmetric multiprocessing]]
- [[Asynchronous array of simple processors]]
- [[Computer cluster]]
- [[DOPIPE]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spatial_architecture