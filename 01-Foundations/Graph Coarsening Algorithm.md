---
title: "Graph Coarsening Algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_Coarsening_Algorithm"
wikipedia_categories: ["Graph algorithms", "Metaheuristics", "Optimization algorithms and methods", "Parallel computing"]
related: ["[[Alpha–beta pruning]]", "[[Communication-avoiding algorithm]]", "[[Euler tour technique]]", "[[Minimax]]", "[[Network simplex algorithm]]", "[[Parallel breadth-first search]]", "[[Parallel metaheuristic]]", "[[A- search algorithm]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]"]
---

# Graph Coarsening Algorithm

A Graph Coarsening Algorithm is a family of metaheuristic algorithms used to reduce the size and complexity of a large graph while preserving its key structural properties. These algorithms form the core of multilevel frameworks, which transform complex optimization problems on massive graphs into smaller, more manageable ones.
The coarsening process involves merging nodes of a graph into clusters called supernodes and aggregating the edges between these clusters to create a new, smaller graph. This process is applied iteratively until the graph is small enough. Then, the original problem (such as partitioning or clustering) is solved on the final small graph, and the solution is progressively mapped back to the larger, original graphs.

## Related

- [[Alpha–beta pruning]]
- [[Communication-avoiding algorithm]]
- [[Euler tour technique]]
- [[Minimax]]
- [[Network simplex algorithm]]
- [[Parallel breadth-first search]]
- [[Parallel metaheuristic]]
- [[A- search algorithm]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_Coarsening_Algorithm