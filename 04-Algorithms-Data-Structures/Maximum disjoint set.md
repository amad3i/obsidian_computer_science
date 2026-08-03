---
title: "Maximum disjoint set"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Maximum_disjoint_set"
wikipedia_categories: ["Computational geometry"]
related: ["[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]", "[[Beta skeleton]]"]
---

# Maximum disjoint set

In computational geometry, a maximum disjoint set (MDS) is a largest set of non-overlapping geometric shapes selected from a given set of candidate shapes.
Every set of non-overlapping shapes is an independent set in the intersection graph of the shapes. Therefore, the MDS problem is a special case of the maximum independent set (MIS) problem. Both problems are NP complete, but finding a MDS may be easier than finding a MIS in two respects:

For the general MIS problem, the best known exact algorithms are exponential. In some geometric intersection graphs, there are sub-exponential algorithms for finding a MDS.
The general MIS problem is hard to approximate and doesn't even have a constant-factor approximation. In some geometric intersection graphs, there are polynomial-time approximation schemes (PTAS) for finding a MDS.
Finding an MDS is important in applications such as automatic label placement, VLSI circuit design, and cellular frequency division multiplexing.
The MDS problem can be generalized by assigning a different weight to each shape and searching for a disjoint set with a maximum total weight.
In the following text, MDS(C) denotes the maximum disjoint set in a set C.

## Related

- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]
- [[Barrier resilience]]
- [[Bentley–Ottmann algorithm]]
- [[Beta skeleton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Maximum_disjoint_set