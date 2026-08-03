---
title: "Late move reductions"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Late_move_reductions"
wikipedia_categories: ["Algorithms and data structures stubs"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Bach's algorithm]]", "[[Badouel intersection algorithm]]", "[[Best bin first]]", "[[Chaitin's algorithm]]", "[[CN2 algorithm]]", "[[Collaborative diffusion]]", "[[Devex algorithm]]", "[[DISCUS]]"]
---

# Late move reductions

Late Move Reductions (abbreviated as LMR) is a non-game specific enhancement to the alpha-beta algorithm and its other variants which attempts to examine a game search tree more efficiently by "pruning" bad nodes. It relies on the assumption that good game-specific move ordering causes a program to search the most likely (good) moves early. If a cut-off is going to happen in a search, the first few moves are the ones most likely to cause them. In games like chess, most programs search winning captures and "killer moves" first. Late move reductions will reduce the search depth for moves searched later at a given node. This heuristic allows the program to search deeper along the critical lines, and play better.
Most of the chess programs (or engines) typically search the first one or two moves in full depth. If the score of the first few moves are lower than alpha, the move is assumed bad. However, if the score of the moves are larger than alpha, the reduced search tells us nothing so we will have to do a full search (called as a fail-low).
This search reduction can lead to a different search space than the pure alpha–beta method which can give different results. Care must be taken to select the reduction criteria or the search will miss some deep threats.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Bach's algorithm]]
- [[Badouel intersection algorithm]]
- [[Best bin first]]
- [[Chaitin's algorithm]]
- [[CN2 algorithm]]
- [[Collaborative diffusion]]
- [[Devex algorithm]]
- [[DISCUS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Late_move_reductions