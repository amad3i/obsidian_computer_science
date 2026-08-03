---
title: "Map (parallel pattern)"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Map_(parallel_pattern)"
wikipedia_categories: ["Parallel computing", "Software design patterns"]
related: ["[[PALLAS]]", "[[Thread pool]]", "[[ABIT BP6]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Advanced Synchronization Facility]]", "[[Aggregate pattern]]"]
---

# Map (parallel pattern)

Map is an idiom in parallel computing where a simple operation is applied to all elements of a sequence, potentially in parallel. It is used to solve embarrassingly parallel problems: those problems that can be decomposed into independent subtasks, requiring no communication/synchronization between the subtasks except a join or barrier at the end.
When applying the map pattern, one formulates an elemental function that captures the operation to be performed on a data item that represents a part of the problem, then applies this elemental function in one or more threads of execution, hyperthreads, SIMD lanes or on multiple computers.
Some parallel programming systems, such as OpenMP and Cilk, have language support for the map pattern in the form of a parallel for loop; languages such as OpenCL and CUDA support elemental functions (as "kernels") at the language level. The map pattern is typically combined with other parallel design patterns. For example, map combined with category reduction gives the MapReduce pattern.

## Related

- [[PALLAS]]
- [[Thread pool]]
- [[ABIT BP6]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Advanced Synchronization Facility]]
- [[Aggregate pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Map_(parallel_pattern)