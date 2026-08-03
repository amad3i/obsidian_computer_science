---
title: "Alpha–beta pruning"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Alpha–beta_pruning"
wikipedia_categories: ["Combinatorial game theory", "Game artificial intelligence", "Graph algorithms", "Optimization algorithms and methods", "Search algorithms"]
related: ["[[Minimax]]", "[[A- search algorithm]]", "[[B-]]", "[[Expectiminimax]]", "[[Iterative deepening A-]]", "[[Proof-number search]]", "[[SMA-]]", "[[Theta-]]", "[[Variation (game tree)]]", "[[Bidirectional search]]"]
---

# Alpha–beta pruning

Alpha–beta pruning is a tree search algorithm that seeks to decrease the number of nodes that are evaluated by the minimax algorithm in its search tree. It is an adversarial search algorithm used commonly for machine playing of two-player combinatorial games (Tic-tac-toe, Chess, Connect 4, etc.). It stops evaluating a move when at least one possibility has been found that proves the move to be worse than a previously examined move. Such moves need not be evaluated further. When applied to a standard minimax tree, it returns the same move as minimax would, but prunes away branches that cannot possibly influence the final decision.

## Related

- [[Minimax]]
- [[A- search algorithm]]
- [[B-]]
- [[Expectiminimax]]
- [[Iterative deepening A-]]
- [[Proof-number search]]
- [[SMA-]]
- [[Theta-]]
- [[Variation (game tree)]]
- [[Bidirectional search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Alpha–beta_pruning