---
title: "Dijkstra–Scholten algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Dijkstra–Scholten_algorithm"
wikipedia_categories: ["Edsger W. Dijkstra", "Graph algorithms", "Termination algorithms"]
related: ["[[Dijkstra's algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]"]
---

# Dijkstra–Scholten algorithm

The Dijkstra–Scholten algorithm (named after Edsger W. Dijkstra and Carel S. Scholten) is an algorithm for detecting termination in a distributed system. The algorithm was proposed by Dijkstra and Scholten in 1980.
First, consider the case of a simple process graph which is a tree. A distributed computation which is tree-structured is not uncommon. Such a process graph may arise when the computation is strictly a divide-and-conquer type. A node starts the computation and divides the problem in two (or more usually, a multiple of 2) roughly equal parts and distribute those parts to other processors. This process continues recursively until the problems are of sufficiently small size to solve in a single processor.

## Related

- [[Dijkstra's algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dijkstra–Scholten_algorithm