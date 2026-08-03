---
title: "Tarjan's off-line lowest common ancestors algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Tarjan's_off-line_lowest_common_ancestors_algorithm"
wikipedia_categories: ["Graph algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[Blossom algorithm]]"]
---

# Tarjan's off-line lowest common ancestors algorithm

In computer science, Tarjan's off-line lowest common ancestors algorithm is an algorithm for computing lowest common ancestors for pairs of nodes in a tree, based on the union-find data structure. The lowest common ancestor of two nodes d and e in a rooted tree T is the node g that is an ancestor of both d and e and that has the greatest depth in T. It is named after Robert Tarjan, who discovered the technique in 1979. Tarjan's algorithm is an offline algorithm; that is, unlike other lowest common ancestor algorithms, it requires that all pairs of nodes for which the lowest common ancestor is desired must be specified in advance. The simplest version of the algorithm uses the union-find data structure, which unlike other lowest common ancestor data structures can take more than constant time per operation when the number of pairs of nodes is similar in magnitude to the number of nodes. A later refinement by Gabow & Tarjan (1983) speeds the algorithm up to linear time.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]
- [[Blossom algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tarjan's_off-line_lowest_common_ancestors_algorithm