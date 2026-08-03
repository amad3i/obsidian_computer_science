---
title: "Distributed memory"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_memory"
wikipedia_categories: ["Distributed computing architecture", "Parallel computing"]
related: ["[[Apache Samza]]", "[[Apache Storm]]", "[[Explicit multi-threading]]", "[[MapReduce]]", "[[Parallelization contract]]", "[[RCUDA]]", "[[Supercomputer]]", "[[Tuple space]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]"]
---

# Distributed memory

In computer science, distributed memory refers to a multiprocessor computer system in which each processor has its own private memory. Computational tasks can only operate on local data, and if remote data are required, the computational task must communicate with one or more remote processors. In contrast, a shared memory multiprocessor offers a single memory space used by all processors. Processors do not have to be aware where data resides, except that there may be performance penalties, and that race conditions are to be avoided.
In a distributed memory system there is typically a processor, a memory, and some form of interconnection that allows programs on each processor to interact with each other. The interconnect can be organised with point to point links or separate hardware can provide a switching network. The network topology is a key factor in determining how the multiprocessor machine scales. The links between nodes can be implemented using some standard network protocol (for example Ethernet), using bespoke network links (used in for example the transputer), or using dual-ported memories.

## Related

- [[Apache Samza]]
- [[Apache Storm]]
- [[Explicit multi-threading]]
- [[MapReduce]]
- [[Parallelization contract]]
- [[RCUDA]]
- [[Supercomputer]]
- [[Tuple space]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_memory