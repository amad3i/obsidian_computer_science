---
title: "Newell's algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Newell's_algorithm"
wikipedia_categories: ["3D computer graphics", "Computer graphics algorithms", "Computer graphics stubs", "History of computing in the United Kingdom", "Science and technology in Cambridgeshire"]
related: ["[[Atkinson dithering]]", "[[Cinematic rendering]]", "[[Geometry Engine]]", "[[Geometry instancing]]", "[[Image plane]]", "[[Image-based meshing]]", "[[Marching cubes]]", "[[Mesh parameterization]]", "[[Micropolygon]]", "[[Painter's algorithm]]"]
---

# Newell's algorithm

Newell's Algorithm is a 3D computer graphics procedure for elimination of polygon cycles in the depth sorting required in hidden surface removal. It was proposed in 1972 by brothers Martin Newell and Dick Newell, and Tom Sancha, while all three were working at CADCentre.
In the depth sorting phase of hidden surface removal, if two polygons have no overlapping extents or extreme minimum and maximum values in the x, y, and z directions, then they can be easily sorted. If two polygons, Q and P, do have overlapping extents in the Z direction, then it is possible that cutting is necessary.

In that case, Newell's algorithm tests the following:

Test for Z overlap; implied in the selection of the face Q from the sort list
The extreme coordinate values in X of the two faces do not overlap (minimax test in X)
The extreme coordinate values in Y of the two faces do not overlap (minimax test in Y)
All vertices of P lie deeper than the plane of Q
All vertices of Q lie closer to the viewpoint than the plane of P
The rasterisation of P and Q do not overlap
The tests are given in order of increasing computational difficulty. 
The polygons must be planar. 
If the tests are all false, then switch the order of P and Q in the sort, record having done so, and try again. If there is an attempt to switch the order of a polygon a second time, there is a visibility cycle, and the polygons must be split. Splitting is accomplished by selecting one polygon and cutting it along the line of intersection with the other polygon. The above tests are again performed, and the algorithm continues until all polygons pass the above tests.

## Related

- [[Atkinson dithering]]
- [[Cinematic rendering]]
- [[Geometry Engine]]
- [[Geometry instancing]]
- [[Image plane]]
- [[Image-based meshing]]
- [[Marching cubes]]
- [[Mesh parameterization]]
- [[Micropolygon]]
- [[Painter's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Newell's_algorithm