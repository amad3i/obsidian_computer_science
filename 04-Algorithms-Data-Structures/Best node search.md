---
title: "Best node search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Best_node_search"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Best node search

Best node search (BNS), originally known as fuzzified game tree search, is a minimax search algorithm developed in 2011 that optimizes decision-making in game trees. BNS differentiates itself from traditional algorithms by identifying which moves (subtrees) are relatively better than others before calculating their exact minimax values, allowing for more efficient pruning of the search space.
First an initial guess at the minimax value must be made—often derived from statistical heuristics. Then BNS conducts searches that determine whether the minimax of the subtree is smaller or bigger than the guess. It changes the guessed value until either the bounds (alpha and beta) are close enough, or only one subtree remains that can potentially contain the optimal value. These two outcomes mirror the established "prove best" and "disprove rest" strategies in heuristic search theory, respectively. The former establishes tight bounds around the best move's value, while the latter eliminates all suboptimal alternatives.
Notably, BNS yields the optimal node (move) and bounds on its minimax value, but not necessarily the exact minimax value itself. This characteristic makes it particularly suitable for applications where identifying the optimal move is more important than knowing its precise value. Empirical evaluations using random trees suggest that BNS achieves superior efficiency compared to other minimax algorithms.

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

- Wikipedia: https://en.wikipedia.org/wiki/Best_node_search