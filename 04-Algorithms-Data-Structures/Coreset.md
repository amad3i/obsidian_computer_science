---
title: "Coreset"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Coreset"
wikipedia_categories: ["Approximation algorithms", "Computational geometry"]
related: ["[[Convex volume approximation]]", "[[Farthest-first traversal]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Approximation algorithm]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]"]
---

# Coreset

In computational geometry and approximation algorithms, a coreset is a small, possibly weighted subset of an input point set that approximately preserves the value of a specified optimization problem. Solving the problem on the coreset yields a solution whose cost is provably close to the optimal solution for the full dataset. Coresets are widely used in geometric optimization, cluster analysis, data streams, and large-scale machine learning to reduce computational complexity while maintaining theoretical guarantees.
Many geometric optimization problems admit coresets of size bounded by a function of the approximation parameter ε and the dimension, but independent of the input size. When such a coreset can be constructed in linear or near-linear time, it yields a polynomial-time approximation scheme (PTAS) or efficient approximation algorithm.
The concept of coresets emerged in the late 1990s and early 2000s within computational geometry, as part of a broader effort to develop approximation schemes for high-dimensional geometric problems. Early work connected coresets to ε-approximations and ε-nets in range spaces and VC dimension theory. Subsequent research extended the framework to clustering, streaming models, and distributed computation. Over time, coresets became a central tool in large-scale data analysis, particularly for clustering and regression problems, where exact computation on massive datasets is computationally infeasible.

## Related

- [[Convex volume approximation]]
- [[Farthest-first traversal]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Approximation algorithm]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Coreset