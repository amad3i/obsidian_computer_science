---
title: "Triangle strip"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Triangle_strip"
wikipedia_categories: ["Computer graphics", "Triangle geometry"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Barycentric coordinate system]]", "[[Bitmap textures]]"]
---

# Triangle strip

In computer graphics, a triangle strip is a subset of triangles in a triangle mesh with shared vertices, and is a more memory-efficient method of storing information about the mesh. They are more efficient than un-indexed lists of triangles, but usually equally fast or slower than indexed triangle lists. The primary reason to use triangle strips is to reduce the amount of data needed to create a series of triangles. The number of vertices stored in memory is reduced from 3N to N + 2, where N is the number of triangles to be drawn.  This allows for less use of disk space, as well as making them faster to load into RAM.

For example, the four triangles in the diagram, without using triangle strips, would have to be stored and interpreted as four separate triangles: ABC, CBD, CDE, and EDF. However, using a triangle strip, they can be stored simply as a sequence of vertices ABCDEF. This sequence  would be decoded as a set of triangles with vertices at ABC, BCD, CDE and DEF - although the exact order that the vertices are read will not be in left-to-right order as this would result in adjacent triangles facing alternating directions.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Barycentric coordinate system]]
- [[Bitmap textures]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Triangle_strip