---
title: "Suurballe's algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Suurballe's_algorithm"
wikipedia_categories: ["Graph algorithms", "Routing algorithms"]
related: ["[[A- search algorithm]]", "[[B-]]", "[[Contraction hierarchies]]", "[[Dijkstra's algorithm]]", "[[Floyd–Warshall algorithm]]", "[[Iterative deepening A-]]", "[[SMA-]]", "[[Transit node routing]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]"]
---

# Suurballe's algorithm

In theoretical computer science and network routing, Suurballe's algorithm is an algorithm for finding two disjoint paths in a nonnegatively-weighted directed graph, so that both paths connect the same pair of vertices and have minimum total length. The algorithm was conceived by John W. Suurballe and published in 1974. The main idea of Suurballe's algorithm is to use Dijkstra's algorithm to find one path, to modify the weights of the graph edges, and then to run Dijkstra's algorithm a second time. The output of the algorithm is formed by combining these two paths, discarding edges that are traversed in opposite directions by the paths, and using the remaining edges to form the two paths to return as the output.
The modification to the weights is similar to the weight modification in Johnson's algorithm, and preserves the non-negativity of the weights while allowing the second instance of Dijkstra's algorithm to find the correct second path.
The problem of finding two disjoint paths of minimum weight can be seen as a special case of a minimum cost flow problem, where in this case there are two units of "flow" and nodes have unit "capacity". Suurballe's algorithm, also, can be seen as a special case of a minimum cost flow algorithm that repeatedly pushes the maximum possible amount of flow along a shortest augmenting path.
The first path found by Suurballe's algorithm is the shortest augmenting path for the initial (zero) flow, and the second path found by Suurballe's algorithm is the shortest augmenting path for the residual graph left after pushing one unit of flow along the first path.

## Related

- [[A- search algorithm]]
- [[B-]]
- [[Contraction hierarchies]]
- [[Dijkstra's algorithm]]
- [[Floyd–Warshall algorithm]]
- [[Iterative deepening A-]]
- [[SMA-]]
- [[Transit node routing]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Suurballe's_algorithm