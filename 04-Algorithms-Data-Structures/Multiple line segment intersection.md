---
title: "Multiple line segment intersection"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiple_line_segment_intersection"
wikipedia_categories: ["Algorithms and data structures stubs", "Computational geometry", "Geometric algorithms", "Geometric intersection"]
related: ["[[Badouel intersection algorithm]]", "[[Bentley–Ottmann algorithm]]", "[[Euclidean shortest path]]", "[[Line–line intersection]]", "[[Progressive-iterative approximation method]]", "[[Surface-to-surface intersection problem]]", "[[Vertex enumeration problem]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[3SUM]]", "[[Algorithmic Geometry]]"]
---

# Multiple line segment intersection

In computational geometry, the multiple line segment intersection problem supplies a list of line segments in the Euclidean plane and asks whether any two of them intersect (cross).
Simple algorithms examine each pair of segments. However, if a large number of possibly intersecting segments are to be checked, this becomes increasingly inefficient since most pairs of segments are not close to one another in a typical input sequence.  The most common, and more efficient, way to solve this problem for a high number of segments is to use a sweep line algorithm, where we imagine a line sliding across the line segments and we track which line segments it intersects at each point in time using a dynamic data structure based on binary search trees. The Shamos–Hoey algorithm applies this principle to solve the line segment intersection detection problem, as stated above, of determining whether or not a set of line segments has an intersection; the Bentley–Ottmann algorithm works by the same principle to list all intersections in logarithmic time per intersection.

## Related

- [[Badouel intersection algorithm]]
- [[Bentley–Ottmann algorithm]]
- [[Euclidean shortest path]]
- [[Line–line intersection]]
- [[Progressive-iterative approximation method]]
- [[Surface-to-surface intersection problem]]
- [[Vertex enumeration problem]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[3SUM]]
- [[Algorithmic Geometry]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiple_line_segment_intersection