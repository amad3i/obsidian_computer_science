---
title: "Fork–join model"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Fork–join_model"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Fork–join model

In parallel computing, the fork–join model is a way of setting up and executing parallel programs, such that execution branches off in parallel at designated points in the program, to "join" (merge) at a subsequent point and resume sequential execution. Parallel sections may fork recursively until a certain task granularity is reached.  Fork–join can be considered a parallel design pattern. It was formulated as early as 1963.
By nesting fork–join computations recursively, one obtains a parallel version of the divide and conquer paradigm, expressed by the following generic pseudocode:

solve(problem):
    if problem is small enough:
        solve problem directly (sequential algorithm)
    else:
        for part in subdivide(problem)
            fork subtask to solve(part)
        join all subtasks spawned in previous loop
        return combined results

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

- Wikipedia: https://en.wikipedia.org/wiki/Fork–join_model