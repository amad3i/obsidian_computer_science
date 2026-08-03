---
title: "Coscheduling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Coscheduling"
wikipedia_categories: ["Parallel computing", "Processor scheduling algorithms"]
related: ["[[Work stealing]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]"]
---

# Coscheduling

Coscheduling is the principle for concurrent systems of scheduling related processes to run on different processors at the same time (in parallel). There are various specific implementations to realize this.
If an application consists of a collection of processes working closely together, and if some but not all of the processes are scheduled for execution, the executing processes may attempt to communicate with those that are not executing, which will cause them to block.  Eventually the other processes will be scheduled for execution, but by this time the situation may be reversed so that these processes also block waiting for interactions with others.  As a result, the application makes progress at the rate of at most one interprocess interaction per time slice, and will have low throughput and high latency.

## Related

- [[Work stealing]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Coscheduling