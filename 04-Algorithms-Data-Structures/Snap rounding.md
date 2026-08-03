---
title: "Snap rounding"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Snap_rounding"
wikipedia_categories: ["Algorithms", "Algorithms and data structures stubs"]
related: ["[[Collaborative diffusion]]", "[[Devex algorithm]]", "[[DONE]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]"]
---

# Snap rounding

Snap rounding is a method of approximating line segment locations by creating a grid and placing each point in the centre of a cell (pixel) of the grid.  The method preserves certain topological properties of the arrangement of line segments.
Drawbacks include the potential interpolation of additional vertices in  line segments (lines become polylines), the arbitrary closeness of a point to a non-incident edge, and arbitrary numbers of intersections between input line-segments.   The 3 dimensional case is worse, with a polyhedral subdivision of complexity n becoming complexity O(n4).
There are more refined algorithms to cope with some of these issues, for example  iterated snap rounding guarantees a "large" separation between points and non-incident edges.

## Related

- [[Collaborative diffusion]]
- [[Devex algorithm]]
- [[DONE]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Snap_rounding