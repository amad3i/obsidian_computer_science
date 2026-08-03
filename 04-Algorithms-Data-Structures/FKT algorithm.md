---
title: "FKT algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/FKT_algorithm"
wikipedia_categories: ["Graph algorithms", "Planar graphs"]
related: ["[[Tutte path]]", "[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]"]
---

# FKT algorithm

The Fisher–Kasteleyn–Temperley (FKT) algorithm, named after Michael Fisher, Pieter Kasteleyn, and Neville Temperley, counts the number of perfect matchings in a planar graph in polynomial time. This same task is #P-complete for general graphs. For matchings that are not required to be perfect, counting them remains #P-complete even for planar graphs. The key idea of the FKT algorithm is to convert the problem into a Pfaffian computation of a skew-symmetric matrix derived from a planar embedding of the graph. The Pfaffian of this matrix is then computed efficiently using standard determinant algorithms.

## Related

- [[Tutte path]]
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

- Wikipedia: https://en.wikipedia.org/wiki/FKT_algorithm