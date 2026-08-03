---
title: "Expectiminimax"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Expectiminimax"
wikipedia_categories: ["Combinatorial game theory", "Game artificial intelligence", "Search algorithms", "Trees (data structures)"]
related: ["[[Alpha–beta pruning]]", "[[Minimax]]", "[[Variation (game tree)]]", "[[A- search algorithm]]", "[[B-]]", "[[Combinatorial search]]", "[[Finger search]]", "[[Finger search tree]]", "[[Iterative deepening A-]]", "[[Move generation]]"]
---

# Expectiminimax

The expectiminimax algorithm is a variation of the minimax algorithm, for use in artificial intelligence systems that play two-player zero-sum games, such as backgammon, in which the outcome depends on a combination of the player's skill and chance elements such as dice rolls. In addition to "min" and "max" nodes of the traditional minimax tree, this variant has "chance" ("move by nature") nodes, which take the expected value of a random event occurring. In game theory terms, an expectiminimax tree is the game tree of an extensive-form game of perfect, but incomplete information.
In the traditional minimax method, the levels of the tree alternate from max to min until the depth limit of the tree has been reached. In an expectiminimax tree, the "chance" nodes are interleaved with the max and min nodes. Instead of taking the max or min of the utility values of their children, chance nodes take a weighted average, with the weight being the probability that child is reached.
The interleaving depends on the game. Each "turn" of the game is evaluated as a "max" node (representing the AI player's turn), a "min" node (representing a potentially-optimal opponent's turn), or a "chance" node (representing a random effect or player).
For example, consider a game in which each round consists of a single die throw, and then decisions made by first the AI player, and then another intelligent opponent. The order of nodes in this game would alternate between "chance", "max" and then "min".

## Related

- [[Alpha–beta pruning]]
- [[Minimax]]
- [[Variation (game tree)]]
- [[A- search algorithm]]
- [[B-]]
- [[Combinatorial search]]
- [[Finger search]]
- [[Finger search tree]]
- [[Iterative deepening A-]]
- [[Move generation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Expectiminimax