---
title: "Superscalar processor"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Superscalar_processor"
wikipedia_categories: ["Classes of computers", "Computer architecture", "Parallel computing", "Superscalar microprocessors"]
related: ["[[Cellular architecture]]", "[[Single instruction, multiple threads]]", "[[Spatial architecture]]", "[[Amorphous computing]]", "[[Asymmetric multiprocessing]]", "[[Computer cluster]]", "[[Dataflow architecture]]", "[[DOPIPE]]", "[[Fifth Generation Computer Systems]]", "[[Harvard architecture]]"]
---

# Superscalar processor

A superscalar processor (or multiple-issue processor) is a CPU that implements a form of parallelism called instruction-level parallelism within a single processor. In contrast to a scalar processor, which can execute at most one single instruction per clock cycle, a superscalar processor can execute or start executing more than one instruction during a clock cycle by simultaneously dispatching multiple instructions to different execution units on the processor. It therefore allows more throughput (the number of instructions that can be executed in a unit of time which can even be less than 1) than would otherwise be possible at a given clock rate. Each execution unit is not a separate processor (or a core if the processor is a multi-core processor), but an execution resource within a single CPU such as an arithmetic logic unit.
While a superscalar CPU is typically also pipelined, superscalar and pipelining execution are considered different performance enhancement techniques. The former (superscalar) executes multiple instructions in parallel by using multiple execution units, whereas the latter (pipeline) executes multiple instructions in the same execution unit in parallel by dividing the execution unit into different phases.  In the "Simple superscalar pipeline" figure, fetching two instructions at the same time is superscaling, and fetching the next two before the first pair has been written back is pipelining.
The superscalar technique is traditionally associated with several identifying characteristics (within a given CPU):

Instructions are issued from a sequential instruction stream
The CPU dynamically checks for data dependencies between instructions at run time (versus software checking at compile time)
The CPU can execute multiple instructions per clock cycle

## Related

- [[Cellular architecture]]
- [[Single instruction, multiple threads]]
- [[Spatial architecture]]
- [[Amorphous computing]]
- [[Asymmetric multiprocessing]]
- [[Computer cluster]]
- [[Dataflow architecture]]
- [[DOPIPE]]
- [[Fifth Generation Computer Systems]]
- [[Harvard architecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Superscalar_processor