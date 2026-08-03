---
title: "Fractional cascading"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Fractional_cascading"
wikipedia_categories: ["Geometric data structures", "Graph data structures", "Search algorithms"]
related: ["[[Geometric hashing]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[Abstract semantic graph]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]"]
---

# Fractional cascading

In computer science, fractional cascading is a technique to speed up a sequence of binary searches for the same value in a sequence of related data structures. The first binary search in the sequence takes a logarithmic amount of time, as is standard for binary searches, but successive searches in the sequence are faster. The original version of fractional cascading, introduced in two papers by Chazelle and Guibas in 1986 (Chazelle & Guibas 1986a; Chazelle & Guibas 1986b), combined the idea of cascading, originating in range searching data structures of Lueker (1978) and Willard (1978), with the idea of fractional sampling, which originated in Chazelle (1983). Later authors introduced more complex forms of fractional cascading that allow the data structure to be maintained as the data changes by a sequence of discrete insertion and deletion events.

## Related

- [[Geometric hashing]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[Abstract semantic graph]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fractional_cascading