---
title: "Move generation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Move_generation"
wikipedia_categories: ["Abstract strategy games", "Combinatorial game theory", "Computer chess", "Game theory", "Search algorithms"]
related: ["[[Variation (game tree)]]", "[[Alpha–beta pruning]]", "[[Expectiminimax]]", "[[Minimax]]", "[[Move ordering]]", "[[Nolot]]", "[[Null-move heuristic]]", "[[Sudoku solving algorithms]]", "[[Zugzwang]]", "[[(1+ε)-approximate nearest neighbor search]]"]
---

# Move generation

Move generation is the computational process by which a program identifies the legal moves available from a given game state in computer chess and generally other strategy games. In general game playing, the engine must produce only valid moves before evaluation can begin. Pseudo-legal moves follow basic movement rules, and fully legal moves satisfy all higher-level constraints such as check (chess). Because the number of possible positions grow exponentially with search depth, move generation gives a major effect on speed and search.
The field developed alongside early chess programming in the 1950s and later progressed through new board representations, data structures and hardware support. Early systems depended on simple array-based boards and strict square-by-square testing and later programs used methods such as the mailbox board, rotated bitboards and magic bitboards. Some engines also used move generation using custom chips, like Belle and Deep Blue.

## Related

- [[Variation (game tree)]]
- [[Alpha–beta pruning]]
- [[Expectiminimax]]
- [[Minimax]]
- [[Move ordering]]
- [[Nolot]]
- [[Null-move heuristic]]
- [[Sudoku solving algorithms]]
- [[Zugzwang]]
- [[(1+ε)-approximate nearest neighbor search]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Move_generation