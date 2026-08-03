---
title: "METIS"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/METIS"
wikipedia_categories: ["Algorithms and data structures stubs", "Graph algorithms", "Mathematical software"]
related: ["[[Chaitin's algorithm]]", "[[Knuth's Simpath algorithm]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Bach's algorithm]]", "[[Badouel intersection algorithm]]"]
---

# METIS

METIS is a software package for graph partitioning that implements various multilevel algorithms. METIS' multilevel approach has three phases and comes with several algorithms for each phase:

Coarsen the graph by generating a sequence of graphs G0, G1, ..., GN, where G0 is the original graph and for each 0 ≤ i < j ≤ N, the number of vertices in Gi is greater than the number of vertices in Gj.
Compute a partition of GN
Project the partition back through the sequence in the order of GN, ..., G0, refining it with respect to each graph.
The final partition computed during the third phase (the refined partition projected onto G0) is a partition of the original graph. 
According to Metis authors Karypis and Kumar, "Metis is the Greek word for wisdom. Metis was a titaness in Greek mythology. She was the consort of Zeus and the mother of Athena. She presided over all wisdom and knowledge".

## Related

- [[Chaitin's algorithm]]
- [[Knuth's Simpath algorithm]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Bach's algorithm]]
- [[Badouel intersection algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/METIS