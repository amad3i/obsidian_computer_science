---
title: "Reverse-delete algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Reverse-delete_algorithm"
wikipedia_categories: ["Graph algorithms", "Spanning tree"]
related: ["[[Borůvka's algorithm]]", "[[Christofides algorithm]]", "[[Kruskal's algorithm]]", "[[Minimum bottleneck spanning tree]]", "[[Prim's algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]"]
---

# Reverse-delete algorithm

The reverse-delete algorithm is an algorithm in graph theory used to obtain a minimum spanning tree from a given connected, edge-weighted graph.  It first appeared in Kruskal (1956), but it should not be confused with Kruskal's algorithm which appears in the same paper. If the graph is disconnected, this algorithm will find a minimum spanning tree for each disconnected part of the graph.  The set of these minimum spanning trees is called a minimum spanning forest, which contains every vertex in the graph.
This algorithm is a greedy algorithm, choosing the best choice given any situation.  It is the reverse of Kruskal's algorithm, which is another greedy algorithm to find a minimum spanning tree.  Kruskal’s algorithm starts with an empty graph and adds edges while the Reverse-Delete algorithm starts with the original graph and deletes edges from it.  The algorithm works as follows:

Start with graph G, which contains a list of edges E.
Go through E in decreasing order of edge weights.
For each edge, check if deleting the edge will further disconnect the graph.
Perform any deletion that does not lead to additional disconnection.

## Related

- [[Borůvka's algorithm]]
- [[Christofides algorithm]]
- [[Kruskal's algorithm]]
- [[Minimum bottleneck spanning tree]]
- [[Prim's algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reverse-delete_algorithm