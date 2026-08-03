---
title: "Widest path problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Widest_path_problem"
wikipedia_categories: ["Computational problems in graph theory", "Graph algorithms", "Network theory", "Polynomial-time problems"]
related: ["[[K shortest path routing]]", "[[Network simplex algorithm]]", "[[Seidel's algorithm]]", "[[Bellman–Ford algorithm]]", "[[Centrality]]", "[[Floyd–Warshall algorithm]]", "[[Graph edit distance]]", "[[Graph isomorphism problem]]", "[[Group centrality]]", "[[Hierarchical closeness]]"]
---

# Widest path problem

In graph algorithms, the widest path problem is the problem of finding a path between two designated vertices in a weighted graph, maximizing the weight of the minimum-weight edge in the path. The widest path problem is also known as the maximum capacity path problem. It is possible to adapt most shortest path algorithms to compute widest paths, by modifying them to use the bottleneck distance instead of path length. However, in many cases even faster algorithms are possible.
For instance, in a graph that represents connections between routers in the Internet, where the weight of an edge represents the bandwidth of a connection between two routers, the widest path problem is the problem of finding an end-to-end path between two Internet nodes that has the maximum possible bandwidth.  The smallest edge weight on this path is known as the capacity or bandwidth of the path. As well as its applications in network routing, the widest path problem is also an important component of the Schulze method for deciding the winner of a multiway election, and has been applied to digital compositing, metabolic pathway analysis, and the computation of maximum flows.
A closely related problem, the minimax path problem or bottleneck shortest path problem asks for the path that minimizes the maximum weight of any of its edges. It has applications that include transportation planning. Any algorithm for the widest path problem can be transformed into an algorithm for the minimax path problem, or vice versa, by reversing the sense of all the weight comparisons performed by the algorithm, or equivalently by replacing every edge weight by its negation.

## Related

- [[K shortest path routing]]
- [[Network simplex algorithm]]
- [[Seidel's algorithm]]
- [[Bellman–Ford algorithm]]
- [[Centrality]]
- [[Floyd–Warshall algorithm]]
- [[Graph edit distance]]
- [[Graph isomorphism problem]]
- [[Group centrality]]
- [[Hierarchical closeness]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Widest_path_problem