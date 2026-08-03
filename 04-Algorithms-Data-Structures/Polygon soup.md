---
title: "Polygon soup"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Polygon_soup"
wikipedia_categories: ["3D computer graphics", "Computer graphics data structures", "Computer graphics stubs", "Geometry stubs"]
related: ["[[Triangle mesh]]", "[[Geometry Engine]]", "[[Geometry instancing]]", "[[Image plane]]", "[[Mesh parameterization]]", "[[Micropolygon]]", "[[Newell's algorithm]]", "[[Nonobtuse mesh]]", "[[Polygon mesh]]", "[[Relief mapping (computer graphics)]]"]
---

# Polygon soup

A polygon soup is a set of unorganized polygons, typically triangles, before the application of any structuring operation, such as e.g. octree grouping.
The term must not to be confused with the "PolySoup" operation available in the 3D package Houdini, whose goal is to optimize the storage space needed by some piece of geometry through the reduction of the underlying number of polygon soups used in its representation. This is accomplished by removing redundant data points (e.g. vertices with the same position) without altering the topology or assigned properties of the optimized geometry in relation to the input one. As a result of this optimization, there can be savings in the storage and processing of large polygon meshes. These savings can have a bigger impact the larger the input data is. For instance, fluid simulations, particle simulations, rigid-body simulations, environments, and character models can reach into the millions of polygons for feature films, incurring in large storage and read/write costs. In those cases, reducing the number of polygon soups required to represent such data can lead to important savings in storage use and compute time.

## Related

- [[Triangle mesh]]
- [[Geometry Engine]]
- [[Geometry instancing]]
- [[Image plane]]
- [[Mesh parameterization]]
- [[Micropolygon]]
- [[Newell's algorithm]]
- [[Nonobtuse mesh]]
- [[Polygon mesh]]
- [[Relief mapping (computer graphics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Polygon_soup