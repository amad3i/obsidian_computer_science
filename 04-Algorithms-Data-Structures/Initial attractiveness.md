---
title: "Initial attractiveness"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Initial_attractiveness"
wikipedia_categories: ["Graph algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[Blossom algorithm]]"]
---

# Initial attractiveness

The initial attractiveness is a possible extension of the Barabási–Albert model (preferential attachment model). The Barabási–Albert model generates scale-free networks where the degree distribution can be described by a pure power law. However, the degree distribution of most real life networks cannot be described by a power law solely. The most common discrepancies regarding the degree distribution found in real networks are the high degree cut-off (or structural cut-off) and the low degree saturation. The inclusion of initial attractiveness in the Barabási–Albert model addresses the low-degree saturation phenomenon.
Intuitively, it also makes sense since when moving to a new city you can still make new connections even though you don't know anyone. But in the Barabási–Albert model a node that has degree zero has probability 0 of garnering new connections. With initial attractiveness you always have a residual "attractiveness" irrespective of how many connections you already have.

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

- Wikipedia: https://en.wikipedia.org/wiki/Initial_attractiveness