---
title: "Triangle fan"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Triangle_fan"
wikipedia_categories: ["Computer graphics", "Computer graphics stubs"]
related: ["[[4D reconstruction]]", "[[Color clock]]", "[[Colour banding]]", "[[Czekanowski distance]]", "[[Depth peeling]]", "[[Device-independent pixel]]", "[[Drop shadow]]", "[[Fillrate]]", "[[Glyph (data visualization)]]", "[[Gooch shading]]"]
---

# Triangle fan

A triangle fan is a primitive in 3D computer graphics that saves on storage and processing time. It describes a set of connected triangles that share one central vertex (unlike the triangle strip that connects the next vertex point to the last two used vertices to form a triangle), possibly within a triangle mesh. If N is the number of triangles in the fan, the number of vertices describing it is N + 2. This is a considerable improvement over the 3N vertices that are necessary to describe the triangles separately. The graphics pipeline can take advantage by only performing the viewing transformations and lighting calculations once per vertex. While triangle fans were useful back then with flat shading or Gouraud shading objects without textures and limited RAM, today they cost performance with fragment shaders and multisampling rasterization. For this reason, Triangle fans are deprecated in Direct3D10 and later.
Any convex polygon may be triangulated as a single fan, by arbitrarily selecting any point inside it as the center.

## Related

- [[4D reconstruction]]
- [[Color clock]]
- [[Colour banding]]
- [[Czekanowski distance]]
- [[Depth peeling]]
- [[Device-independent pixel]]
- [[Drop shadow]]
- [[Fillrate]]
- [[Glyph (data visualization)]]
- [[Gooch shading]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Triangle_fan