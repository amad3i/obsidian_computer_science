---
title: "Loop-level parallelism"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Loop-level_parallelism"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Loop-level parallelism

Loop-level parallelism is a form of parallelism in software programming that is concerned with extracting parallel tasks from loops. The opportunity for loop-level parallelism often arises in computing programs where data is stored in random access data structures. Where a sequential program will iterate over the data structure and operate on indices one at a time, a program exploiting loop-level parallelism will use multiple threads or processes which operate on some or all of the indices at the same time. Such parallelism provides a speedup to overall execution time of the program, typically in line with Amdahl's law.

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

- Wikipedia: https://en.wikipedia.org/wiki/Loop-level_parallelism