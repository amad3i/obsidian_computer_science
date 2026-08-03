---
title: "Loop scheduling"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Loop_scheduling"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Loop scheduling

In parallel computing, loop scheduling is the problem of assigning proper iterations of parallelizable loops among n processors to achieve load balancing and maintain data locality with minimum dispatch overhead.
Typical loop scheduling methods are:

static even scheduling: evenly divide loop iteration space into n chunks and assign each chunk to a processor
dynamic scheduling: a chunk of loop iteration is dispatched at runtime by an idle processor. When the chunk size is 1 iteration, it is also called self-scheduling.
guided scheduling: similar to dynamic scheduling, but the chunk sizes per dispatch keep shrinking until reaching a preset value.

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

- Wikipedia: https://en.wikipedia.org/wiki/Loop_scheduling