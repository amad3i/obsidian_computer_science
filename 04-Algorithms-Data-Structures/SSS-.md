---
title: "SSS*"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/SSS*"
wikipedia_categories: ["Search algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# SSS*

SSS* is a search algorithm introduced by George Stockman in 1979. It conducts a state space search traversing a game tree in a best-first fashion similar to that of the A* search algorithm.
SSS* is based on the notion of solution trees. Informally, a solution tree can be formed from any arbitrary game tree by pruning the number of branches at each MAX node to one. Such a tree represents a complete strategy for MAX, since it specifies exactly one MAX action for every possible sequence of moves made by the opponent. Given a game tree, SSS* searches through the space of partial solution trees, gradually analyzing larger and larger subtrees, eventually producing a single solution tree with the same root and Minimax value as the original game tree. SSS* never examines a node that alpha–beta pruning would prune, and may prune some branches that alpha–beta would not. Stockman speculated that SSS* may therefore be a better general algorithm than alpha–beta. However, Igor Roizen and Judea Pearl have shown that the savings in the number of positions that SSS* evaluates relative to alpha/beta is limited and generally not enough to compensate for the increase in other resources (e.g., the storing and sorting of a list of nodes made necessary by the best-first nature of the algorithm). However, Aske Plaat, Jonathan Schaeffer, Wim Pijls and Arie de Bruin have shown that a sequence of null-window alpha–beta calls is equivalent to SSS* (i.e., it expands the same nodes in the same order) when alpha–beta is used with a transposition table, as is the case in all game-playing programs for chess, checkers, etc. Now the storing and sorting of the OPEN list were no longer necessary. This allowed the implementation of (an algorithm equivalent to) SSS* in tournament quality game-playing programs. Experiments showed that it did indeed perform better than Alpha–Beta in practice, but that it did not beat NegaScout.
The reformulation of a best-first algorithm as a sequence of depth-first calls prompted the formulation of a class of null-window alpha–beta algorithms, of which MTD(f) is the best known example.

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

- Wikipedia: https://en.wikipedia.org/wiki/SSS*