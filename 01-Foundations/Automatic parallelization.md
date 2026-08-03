---
title: "Automatic parallelization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Automatic_parallelization"
wikipedia_categories: ["Compiler optimizations", "Parallel computing"]
related: ["[[Automatic vectorization]]", "[[Flattening transformation]]", "[[Loop unrolling]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]"]
---

# Automatic parallelization

Automatic parallelization, also auto parallelization, or autoparallelization refers to converting sequential code into multi-threaded and/or vectorized code in order to use multiple processors simultaneously in a shared-memory multiprocessor (SMP) machine. Fully automatic parallelization of sequential programs is a challenge because it requires complex program analysis and the best approach may depend upon parameter values that are not known at compilation time.
The programming control structures on which autoparallelization places the most focus are loops, because, in general, most of the execution time of a program takes place inside some form of loop.
There are two main approaches to parallelization of loops: pipelined multi-threading and cyclic multi-threading. For example, consider a loop that on each iteration applies a hundred operations, and runs for a thousand iterations.  This can be thought of as a grid of 100 columns by 1000 rows, a total of 100,000 operations. Cyclic multi-threading assigns each row to a different thread. Pipelined multi-threading assigns each column to a different thread.

## Related

- [[Automatic vectorization]]
- [[Flattening transformation]]
- [[Loop unrolling]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Automatic_parallelization