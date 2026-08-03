---
title: "Reverse-search algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Reverse-search_algorithm"
wikipedia_categories: ["Combinatorial algorithms", "Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Reverse-search algorithm

Reverse-search algorithms are a class of algorithms for generating all objects of a given size, from certain classes of combinatorial objects. In many cases, these methods allow the objects to be generated in polynomial time per object, using only enough memory to store a constant number of objects (polynomial space). (Generally, however, they are not classed as polynomial-time algorithms, because the number of objects they generate is exponential.) They work by organizing the objects to be generated into a spanning tree of their state space, and then performing a depth-first search of this tree.
Reverse-search algorithms were introduced by David Avis and Komei Fukuda in 1991, for problems of generating the vertices of convex polytopes and the cells of arrangements of hyperplanes. They were formalized more broadly by Avis and Fukuda in 1996.

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

- Wikipedia: https://en.wikipedia.org/wiki/Reverse-search_algorithm