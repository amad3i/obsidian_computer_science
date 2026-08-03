---
title: "Weisfeiler Leman graph isomorphism test"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Weisfeiler_Leman_graph_isomorphism_test"
wikipedia_categories: ["Graph algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[Blossom algorithm]]"]
---

# Weisfeiler Leman graph isomorphism test

In graph theory, the Weisfeiler Leman graph isomorphism test is a heuristic test for the existence of an isomorphism between two graphs G and H. It is a generalization of the color refinement algorithm and has been first described by Weisfeiler and Leman in 1968. The original formulation is based on graph canonization, a normal form for graphs, while there is also a combinatorial interpretation in the spirit of fibrations of graphs / color refinement and a connection to logic.
The one-dimensional version, also known as color refinement, repeatedly updates the color of each vertex according to the multiset of colors of its neighbors until a stable color configuration is reached. If they are different for G and H, they are non-isomorphic; if they receive the same coloring, the test is inconclusive.
An example of two non-isomorphic graphs the Weisfeiler–Leman test cannot distinguish is given here.

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

- Wikipedia: https://en.wikipedia.org/wiki/Weisfeiler_Leman_graph_isomorphism_test