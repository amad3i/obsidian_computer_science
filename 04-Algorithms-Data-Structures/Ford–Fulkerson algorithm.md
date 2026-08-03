---
title: "Ford–Fulkerson algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Ford–Fulkerson_algorithm"
wikipedia_categories: ["Graph algorithms", "Network flow problem"]
related: ["[[Dinic's algorithm]]", "[[Edmonds–Karp algorithm]]", "[[Gomory–Hu tree]]", "[[Network flow problem]]", "[[Network simplex algorithm]]", "[[Push–relabel maximum flow algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]"]
---

# Ford–Fulkerson algorithm

The Ford–Fulkerson method or Ford–Fulkerson algorithm (FFA) is a greedy algorithm that computes the maximum flow in a flow network. It is sometimes called a "method" instead of an "algorithm" as the approach to finding augmenting paths in a residual graph is not fully specified or it is specified in several implementations with different running times. It was published in 1956 by L. R. Ford Jr. and D. R. Fulkerson. The name "Ford–Fulkerson" is often also used for the Edmonds–Karp algorithm, which is a fully defined implementation of the Ford–Fulkerson method.
The idea behind the algorithm is as follows: as long as there is a path from the source (start node) to the sink (end node), with available capacity on all edges in the path, we send flow along one of the paths. Then we find another path, and so on. A path with available capacity is called an augmenting path.

## Related

- [[Dinic's algorithm]]
- [[Edmonds–Karp algorithm]]
- [[Gomory–Hu tree]]
- [[Network flow problem]]
- [[Network simplex algorithm]]
- [[Push–relabel maximum flow algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ford–Fulkerson_algorithm