---
title: "Dynamic connectivity"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_connectivity"
wikipedia_categories: ["Graph algorithms", "Graph data structures"]
related: ["[[A- search algorithm]]", "[[Abstract semantic graph]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]"]
---

# Dynamic connectivity

In computing and graph theory, a dynamic connectivity structure is a data structure that dynamically maintains information about the connected components of a graph.
The set V of vertices of the graph is fixed, but the set E of edges can change. The three cases, in order of difficulty, are:

Edges are only added to the graph (this can be called incremental connectivity);
Edges are only deleted from the graph (this can be called decremental connectivity);
Edges can be either added or deleted (this can be called fully dynamic connectivity).
After each addition/deletion of an edge, the dynamic connectivity structure should adapt itself such that it can give quick answers to queries of the form "is there a path between x and y?" (equivalently: "do vertices x and y belong to the same connected component?").

## Related

- [[A- search algorithm]]
- [[Abstract semantic graph]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_connectivity