---
title: "Painter's algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Painter's_algorithm"
wikipedia_categories: ["3D computer graphics", "Computer graphics algorithms"]
related: ["[[Cinematic rendering]]", "[[Image-based meshing]]", "[[Marching cubes]]", "[[Newell's algorithm]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]"]
---

# Painter's algorithm

The painter's algorithm (also depth-sort algorithm and priority fill) is an algorithm for visible surface determination in 3D computer graphics that works on a polygon-by-polygon basis rather than a pixel-by-pixel, row by row, or area by area basis of other hidden-surface determination algorithms. The painter's algorithm creates images by sorting the polygons within the image by their depth and placing each polygon in order from the farthest to the closest object.

The painter's algorithm was initially proposed as a basic method to address the hidden-surface determination problem by Martin Newell, Richard Newell, and Tom Sancha in 1972, while all three were working at CADCentre. The name "painter's algorithm" refers to the technique employed by many painters where they begin by painting distant parts of a scene before parts that are nearer, thereby covering some areas of distant parts. Similarly, the painter's algorithm sorts all the polygons in a scene by their depth and then paints them in this order, farthest to closest. It will paint over the parts that are normally not visible — thus solving the visibility problem — at the cost of having painted invisible areas of distant objects. The ordering used by the algorithm is called a 'depth order' and does not have to respect the numerical distances to the parts of the scene: the essential property of this ordering is, rather, that if one object obscures part of another, then the first object is painted after the object that it obscures. Thus, a valid ordering can be described as a topological ordering of a directed acyclic graph representing occlusions between objects.

## Related

- [[Cinematic rendering]]
- [[Image-based meshing]]
- [[Marching cubes]]
- [[Newell's algorithm]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Painter's_algorithm