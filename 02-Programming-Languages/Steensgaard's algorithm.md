---
title: "Steensgaard's algorithm"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Steensgaard's_algorithm"
wikipedia_categories: ["Algorithms and data structures stubs", "Static program analysis"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[Alias analysis]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Array-access analysis]]", "[[Bach's algorithm]]", "[[Badouel intersection algorithm]]", "[[Best bin first]]", "[[Call graph]]", "[[Chaitin's algorithm]]", "[[CN2 algorithm]]"]
---

# Steensgaard's algorithm

In computer science, Steensgaard's algorithm is a scalable, flow-insensitive, algorithm for pointer analysis. It is often used in compilers, due to its speed (for example, an implementation is available in the LLVM compiler framework). In its original formulation, this algorithm was field-, context-, and array-insensitive.
Steensgaard's algorithm is based on equality constraints, as opposed to Andersen's algorithm, which is based on subset constraints. This allows points-to information to be tracked using a union-find data structure. This choice gives the algorithm its characteristic speed; when implemented using a union-find data structure it is linear space and almost linear time in the size of the input program.
Bjarne Steensgaard's formulation of the algorithm was in terms of type inference and type checking. Steensgaard proposed the points-to analysis for a small imperative but generic pointer language which captures the essential properties of other common languages with pointers, like C. The language semantics and typing rules constitute the analysis.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[Alias analysis]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Array-access analysis]]
- [[Bach's algorithm]]
- [[Badouel intersection algorithm]]
- [[Best bin first]]
- [[Call graph]]
- [[Chaitin's algorithm]]
- [[CN2 algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Steensgaard's_algorithm