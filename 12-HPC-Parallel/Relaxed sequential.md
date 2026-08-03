---
title: "Relaxed sequential"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Relaxed_sequential"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Relaxed sequential

Relaxed sequential in computer science is an execution model describing the ability of a parallel program to run sequentially. If a parallel program has a valid sequential execution it is said to follow a relaxed sequential execution model. It does not need to be efficient.
The word relaxed refers to the notion that serial programs are actually overly constrained by implicit serial dependencies (such as the program counter) and that one can introduce as much parallelism as possible without removing the ability to run sequentially. One can think of this model as being as relaxed as possible while still being able to run correctly in a single thread. That is the goal.
Most parallel programs can run sequentially but will benefit from parallelism when it is present. It is possible to design programs that require parallelism for correct behavior. Algorithms such as producer-consumer that are implemented so as to require two or more threads are one example of requiring concurrency to work properly. For instance, consider a bounded container with a capacity for only three items and a program which has one thread doing “PUT PUT PUT PUT,” and another thread doing “GET GET GET GET,” each doing their actions only four at a time. Such a program requires interleaving (concurrency). A program that requires concurrency is more difficult to debug. It is easier to debug a program that has a valid sequential execution.
Programs designed to require concurrency are more difficult to debug. Programs designed to require concurrency will have performance issues when the number of required threads exceeds the number of hardware threads because time slicing artifacts can hit hard.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Relaxed_sequential