---
title: "Embarrassingly parallel"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Embarrassingly_parallel"
wikipedia_categories: ["Applications of distributed computing", "Distributed computing problems", "Parallel computing"]
related: ["[[Automatic vectorization]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aggregate Level Simulation Protocol]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]"]
---

# Embarrassingly parallel

In parallel computing, an embarrassingly parallel workload or problem (also called embarrassingly parallelizable, perfectly parallel, delightfully parallel or pleasingly parallel) is one where little or no effort is needed to split the problem into a number of parallel tasks. This is due to minimal or no dependency upon communication between the parallel tasks, or for results between them.
These differ from distributed computing problems, which need communication between tasks, especially communication of intermediate results. They are easier to perform on server farms which lack the special infrastructure used in a true supercomputer cluster. They are well-suited to large, Internet-based volunteer computing platforms such as BOINC, and suffer less from parallel slowdown. The opposite of embarrassingly parallel problems are inherently serial problems, which cannot be parallelized at all.
A common example of an embarrassingly parallel problem is 3D video rendering handled by a graphics processing unit, where each frame (forward method) or pixel (ray tracing method) can be handled with no interdependency. Some forms of password cracking are another embarrassingly parallel task that is easily distributed on central processing units, CPU cores, or clusters.

## Related

- [[Automatic vectorization]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aggregate Level Simulation Protocol]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Embarrassingly_parallel