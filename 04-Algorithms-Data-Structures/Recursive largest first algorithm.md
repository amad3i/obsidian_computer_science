---
title: "Recursive largest first algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Recursive_largest_first_algorithm"
wikipedia_categories: ["1979 in computing", "Graph algorithms", "Graph coloring"]
related: ["[[DSatur]]", "[[Misra & Gries edge-coloring algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]"]
---

# Recursive largest first algorithm

The Recursive Largest First (RLF) algorithm is a heuristic for the NP-hard graph coloring problem. It was originally proposed by Frank Leighton in 1979.
The RLF algorithm assigns colors to a graph’s vertices by constructing each color class one at a time. It does this by identifying a maximal independent set of vertices in the graph, assigning these to the same color, and then removing these vertices from the graph. These actions are repeated on the remaining subgraph until no vertices remain. 
To form high-quality solutions (solutions using few colors), the RLF algorithm uses specialized heuristic rules to try to identify "good quality" independent sets. These heuristics make the RLF algorithm exact for bipartite, cycle, and wheel graphs. In general, however, the algorithm is approximate and may well return solutions that use more colors than the graph’s chromatic number.

## Related

- [[DSatur]]
- [[Misra & Gries edge-coloring algorithm]]
- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Recursive_largest_first_algorithm