---
title: "DSatur"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/DSatur"
wikipedia_categories: ["1979 in computing", "Graph algorithms", "Graph coloring"]
related: ["[[Recursive largest first algorithm]]", "[[Misra & Gries edge-coloring algorithm]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]"]
---

# DSatur

DSatur is a graph colouring algorithm put forward by Daniel Brélaz in 1979. Similarly to the greedy colouring algorithm, DSatur colours the vertices of a graph one after another, adding a previously unused colour when needed. Once a new vertex has been coloured, the algorithm determines which of the remaining uncoloured vertices has the highest number of colours in its neighbourhood and colours this vertex next. Brélaz defines this number as the degree of saturation of a given vertex. The contraction of the term "degree of saturation" forms the name of the algorithm. DSatur is a heuristic graph colouring algorithm, yet produces exact results for bipartite, cycle, and wheel graphs. DSatur has also been referred to as saturation LF in the literature.

## Related

- [[Recursive largest first algorithm]]
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

- Wikipedia: https://en.wikipedia.org/wiki/DSatur