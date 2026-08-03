---
title: "Bidirectional search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bidirectional_search"
wikipedia_categories: ["Graph algorithms", "Search algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[B-]]", "[[Breadth-first search]]", "[[Contraction hierarchies]]", "[[D-]]", "[[Depth-first search]]", "[[Dijkstra's algorithm]]", "[[Fringe search]]", "[[Iterative deepening A-]]"]
---

# Bidirectional search

Bidirectional search is a graph search algorithm that finds a shortest path from an initial vertex to a goal vertex in a directed graph. It runs two simultaneous searches: one forward from the initial state, and one backward from the goal, stopping when the two meet. The reason for this approach is that in many cases it is faster: for instance, in a simplified model of search problem complexity in which both searches expand a tree with branching factor b, and the distance from start to goal is d, each of the two searches has complexity O(bd/2) (in Big O notation), and the sum of these two search times is much less than the O(bd) complexity that would result from a single search from the beginning to the goal.
Andrew Goldberg and others explained the correct termination conditions for the bidirectional version of Dijkstra’s Algorithm.
As in A* search, bi-directional search can be guided by a heuristic estimate of the remaining distance to the goal (in the forward tree) or from the start (in the backward tree).
Ira Pohl was the first one to design and implement a bi-directional heuristic search algorithm. Search trees emanating from the start and goal nodes failed to meet in the middle of the solution space.  The BHFFA algorithm of de Champeaux fixed this defect.
A solution found by the uni-directional A* algorithm using an admissible heuristic has a shortest path length; the same property holds for the BHFFA2 bidirectional heuristic version described by de Champeaux . BHFFA2 has, among others, more careful termination conditions than BHFFA.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[B-]]
- [[Breadth-first search]]
- [[Contraction hierarchies]]
- [[D-]]
- [[Depth-first search]]
- [[Dijkstra's algorithm]]
- [[Fringe search]]
- [[Iterative deepening A-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bidirectional_search