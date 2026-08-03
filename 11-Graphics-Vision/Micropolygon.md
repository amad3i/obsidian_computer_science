---
title: "Micropolygon"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Micropolygon"
wikipedia_categories: ["3D computer graphics", "Computer graphics stubs"]
related: ["[[Geometry Engine]]", "[[Geometry instancing]]", "[[Image plane]]", "[[Mesh parameterization]]", "[[Newell's algorithm]]", "[[Polygon soup]]", "[[Relief mapping (computer graphics)]]", "[[Retopology]]", "[[Schlick's approximation]]", "[[Specularity]]"]
---

# Micropolygon

In 3D computer graphics, a micropolygon (or μ-polygon) is a polygon that is very small relative to the image being rendered. Commonly, the size of a micropolygon is close to or even less than the area of a pixel. Micropolygons allow a renderer to create a highly detailed image.
The concept of micropolygons was developed within the Reyes algorithm, in which geometric primitives are tessellated at render time into a rectangular grid of tiny, four-sided polygons. A shader might fill each micropolygon with a single color or assign colors on a per-vertex basis. Shaders that operate on micropolygons can process an entire grid of them at once in SIMD fashion. This often leads to faster shader execution, and allows shaders to compute spatial derivatives (e.g. for texture filtering) by comparing values at neighboring micropolygon vertices.
Furthermore, a renderer using micropolygons can support displacement mapping simply by perturbing micropolygon vertices during shading. This displacement is usually not limited to the local surface normal but can be given an arbitrary direction.

## Related

- [[Geometry Engine]]
- [[Geometry instancing]]
- [[Image plane]]
- [[Mesh parameterization]]
- [[Newell's algorithm]]
- [[Polygon soup]]
- [[Relief mapping (computer graphics)]]
- [[Retopology]]
- [[Schlick's approximation]]
- [[Specularity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Micropolygon