---
title: "Uniform binary search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Uniform_binary_search"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Uniform binary search

Uniform binary search is an optimization of the classic binary search algorithm. It was first published by Donald Knuth, in The Art of Computer Programming, who credited its idea to Ashok K. Chandra. It uses a lookup table to update a single array index, rather than taking the midpoint of an upper and a lower bound on each iteration; therefore, it is optimized for architectures (such as Knuth's MIX) on which

a table lookup is generally faster than an addition and a shift, and
many searches will be performed on the same array, or on several arrays of the same length

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

- Wikipedia: https://en.wikipedia.org/wiki/Uniform_binary_search