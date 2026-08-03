---
title: "MTD(f)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/MTD(f)"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# MTD(f)

MTD(f) is an alpha-beta game tree search algorithm modified to use ‘zero-window’ initial search bounds, and memory (usually a transposition table) to reuse intermediate search results. MTD(f) is a shortened form of MTD(n,f) which stands for Memory-enhanced Test Driver with node ‘n’ and value ‘f’. The efficacy of this paradigm depends on a good initial guess, and the supposition that the final minimax value lies in a narrow window around the guess (which becomes an upper/lower bound for the search from root). The memory structure is used to save an initial guess determined elsewhere.
MTD(f) was introduced in 1994 and largely supplanted NegaScout (PVS), the previously dominant search paradigm for chess, checkers, othello and other game automatons.

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

- Wikipedia: https://en.wikipedia.org/wiki/MTD(f)