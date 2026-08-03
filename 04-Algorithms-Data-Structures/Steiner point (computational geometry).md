---
title: "Steiner point (computational geometry)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Steiner_point_(computational_geometry)"
wikipedia_categories: ["Computational geometry"]
related: ["[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]", "[[Beta skeleton]]"]
---

# Steiner point (computational geometry)

In computational geometry, a Steiner point is a point that is not part of the input to a geometric optimization problem but is added during the solution of the problem, to create a better solution than would be possible from the original points alone.
The name of these points comes from the Steiner tree problem, named after Jakob Steiner, in which the goal is to connect the input points by a network of minimum total length. If the input points alone are used as endpoints of the network edges, then the shortest network is their minimum spanning tree. However, shorter networks can often be obtained by adding Steiner points,
and using both the new points and the input points as edge endpoints.
Another problem that uses Steiner points is Steiner triangulation. The goal is to partition an input (such as a point set or polygon) into triangles, meeting edge-to-edge. Both input points and Steiner points may be used as triangle vertices.

## Related

- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]
- [[Barrier resilience]]
- [[Bentley–Ottmann algorithm]]
- [[Beta skeleton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Steiner_point_(computational_geometry)