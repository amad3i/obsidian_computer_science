---
title: "Borůvka's algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Borůvka's_algorithm"
wikipedia_categories: ["Graph algorithms", "Spanning tree"]
related: ["[[Christofides algorithm]]", "[[Kruskal's algorithm]]", "[[Minimum bottleneck spanning tree]]", "[[Prim's algorithm]]", "[[Reverse-delete algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]"]
---

# Borůvka's algorithm

Borůvka's algorithm is a greedy algorithm for finding a minimum spanning tree in a graph,
or a minimum spanning forest in the case of a graph that is not connected.
It was first published in 1926 by Otakar Borůvka as a method of constructing an efficient electricity network for Moravia.
The algorithm was rediscovered by Choquet in 1938; again by Florek,  Łukasiewicz, Perkal, Steinhaus, and Zubrzycki in 1951; and again by Georges Sollin in 1965. This algorithm is frequently called Sollin's algorithm, especially in the parallel computing literature.
The algorithm begins by finding the minimum-weight edge incident to each vertex of the graph, and adding all of those edges to the forest.
Then, it repeats a similar process of finding the minimum-weight edge from each tree constructed so far to a different tree, and adding all of those edges to the forest.
Each repetition of this process reduces the number of trees, within each connected component of the graph, to at most half of this former value,
so after logarithmically many repetitions the process finishes. When it does, the set of edges it has added forms the minimum spanning forest.

## Related

- [[Christofides algorithm]]
- [[Kruskal's algorithm]]
- [[Minimum bottleneck spanning tree]]
- [[Prim's algorithm]]
- [[Reverse-delete algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Borůvka's_algorithm