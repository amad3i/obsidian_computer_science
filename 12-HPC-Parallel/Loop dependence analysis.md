---
title: "Loop dependence analysis"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Loop_dependence_analysis"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Loop dependence analysis

In computer science, loop dependence analysis is a process which can be used to find dependencies within iterations of a loop with the goal of determining different relationships between statements. These dependent relationships are tied to the order in which different statements access memory locations. Using the analysis of these relationships, execution of the loop can be organized to allow multiple processors to work on different portions of the loop in parallel. This is known as parallel processing. In general, loops can consume a lot of processing time when executed as serial code. Through parallel processing, it is possible to reduce the total execution time of a program through sharing the processing load among multiple processors.
The process of organizing statements to allow multiple processors to work on different portions of a loop is often referred to as parallelization. In order to see how we can exploit parallelization, we have to first analyze the dependencies within individual loops. These dependencies will help determine which statements in the loop need to be completed before other statements can start, and which statements in the loop can be executed in parallel with respect to the other statements in the loop. Two general categories of dependencies that will be analyzed in the loop are data dependencies and control dependencies.

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

- Wikipedia: https://en.wikipedia.org/wiki/Loop_dependence_analysis