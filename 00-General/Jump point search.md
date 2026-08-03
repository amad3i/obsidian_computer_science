---
title: "Jump point search"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Jump_point_search"
wikipedia_categories: []
related: []
---

# Jump point search

In computer science, jump point search (JPS) is an optimization to the A* search algorithm for uniform-cost grids. It reduces symmetries in the search procedure by means of graph pruning, eliminating certain nodes in the grid based on assumptions that can be made about the current node's neighbors, as long as certain conditions relating to the grid are satisfied. As a result, the algorithm can consider long "jumps" along straight (horizontal, vertical and diagonal) lines in the grid, rather than the small steps from one grid position to the next that ordinary A* considers.
Jump point search preserves A*'s optimality, while potentially reducing its running time by an order of magnitude.

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Jump_point_search