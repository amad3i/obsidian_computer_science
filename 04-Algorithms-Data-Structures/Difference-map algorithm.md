---
title: "Difference-map algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Difference-map_algorithm"
wikipedia_categories: ["Constraint programming", "Search algorithms"]
related: ["[[Backjumping]]", "[[Look-ahead (backtracking)]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[Algorithm selection]]", "[[All nearest smaller values]]", "[[Allen's interval algebra]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]"]
---

# Difference-map algorithm

The difference-map algorithm is a search algorithm for general constraint satisfaction problems. It is a meta-algorithm in the sense that it is built from more basic algorithms that perform projections onto constraint sets. From a mathematical perspective, the difference-map algorithm is a dynamical system based on a mapping of Euclidean space. Solutions are encoded as fixed points of the mapping.
Although originally conceived as a general method for solving the phase problem, the difference-map algorithm has been used for the boolean satisfiability problem, protein structure prediction, Ramsey numbers, diophantine equations, and Sudoku, as well as sphere- and disk-packing problems. Since these applications include NP-complete problems, the scope of the difference map is that of an incomplete algorithm. Whereas incomplete algorithms can efficiently verify solutions (once a candidate is found), they cannot prove that a solution does not exist.
The difference-map algorithm is a generalization of two iterative methods: Fienup's Hybrid input output (HIO) algorithm for phase retrieval and the Douglas-Rachford algorithm for convex optimization. Iterative methods, in general, have a long history in phase retrieval and convex optimization. The use of this style of algorithm for hard, non-convex problems is a more recent development.

## Related

- [[Backjumping]]
- [[Look-ahead (backtracking)]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[Algorithm selection]]
- [[All nearest smaller values]]
- [[Allen's interval algebra]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Difference-map_algorithm