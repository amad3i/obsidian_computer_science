---
title: "Multiplicative binary search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiplicative_binary_search"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Multiplicative binary search

In computer science, multiplicative binary search is a variation
of binary search that uses a specific permutation of keys in an array instead of the sorted order used by regular binary
search.
Multiplicative binary search was first described by Thomas Standish in 1980.
This algorithm was originally proposed to simplify the midpoint index calculation on small computers without efficient division or shift operations.
On modern hardware, the cache-friendly nature of multiplicative binary search makes it suitable for out-of-core search on block-oriented storage as an alternative to B-trees and B+ trees.  For optimal performance, the branching factor of a B-tree or B+-tree must match the block size of the file system that it is stored on.  The permutation used by multiplicative binary search places the optimal number of keys in the first (root) block, regardless of block size.
Multiplicative binary search is used by some optimizing compilers to implement switch statements.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]
- [[Backjumping]]
- [[Backtracking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiplicative_binary_search