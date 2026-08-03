---
title: "Disjoint-set data structure"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Disjoint-set_data_structure"
wikipedia_categories: ["Amortized data structures", "Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[AVL tree]]", "[[B-]]", "[[Backjumping]]"]
---

# Disjoint-set data structure

In computer science, a disjoint-set data structure, also called a union–find data structure or merge–find set, is a data structure that stores a collection of disjoint (non-overlapping) sets. Equivalently, it stores a partition of a set into disjoint subsets. It provides operations for adding new sets, merging sets (replacing them with their union), and finding a representative member of a set. The last operation makes it possible to determine efficiently whether any two elements belong to the same set or to different sets.
While there are several ways of implementing disjoint-set data structures, in practice they are often identified with a particular implementation known as a disjoint-set forest. This specialized type of forest performs union and find operations in near-constant amortized time. For a sequence of m addition, union, or find operations on a disjoint-set forest with n nodes, the total time required is O(mα(n)), where α(n) is the extremely slow-growing inverse Ackermann function. Although disjoint-set forests do not guarantee this time per operation, each operation rebalances the structure (via tree compression) so that subsequent operations become faster. As a result, disjoint-set forests are both asymptotically optimal and practically efficient.
Disjoint-set data structures play a key role in Kruskal's algorithm for finding the minimum spanning tree of a graph. The importance of minimum spanning trees means that disjoint-set data structures support a wide variety of algorithms. In addition, these data structures find applications in symbolic computation and in compilers, especially for register allocation problems.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[AVL tree]]
- [[B-]]
- [[Backjumping]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Disjoint-set_data_structure