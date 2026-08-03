---
title: "Relief mapping (computer graphics)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Relief_mapping_(computer_graphics)"
wikipedia_categories: ["3D computer graphics", "Computer graphics stubs", "Texture mapping"]
related: ["[[Geometry Engine]]", "[[Geometry instancing]]", "[[Horizon mapping]]", "[[Image plane]]", "[[Mesh parameterization]]", "[[Micropolygon]]", "[[Newell's algorithm]]", "[[Polygon soup]]", "[[Retopology]]", "[[Schlick's approximation]]"]
---

# Relief mapping (computer graphics)

In computer graphics, relief mapping is a texture mapping technique first introduced in 2000 used to render the surface details of three-dimensional objects accurately and efficiently. It can produce accurate depictions of self-occlusion, self-shadowing, and parallax. Relief mapping works by transforming the view direction into tangent space and intersecting the viewing ray with a depth map; in the 2005 real-time GPU formulation, this was implemented as a pixel-driven ray-height-field intersection that maps relief textures onto arbitrary polygonal models and can be applied to deforming surfaces. That formulation did not render surface details at object silhouettes, although later extensions added correct silhouette rendering. A 2006 multilayer extension generalized relief mapping to non-height-field surface details, enabling real-time rendering of structures such as weave patterns. Relief mapping is highly comparable in both function and approach to another displacement texture mapping technique, parallax occlusion mapping, considering that they both rely on ray marching, though the two are not to be confused with each other, as parallax occlusion mapping uses reverse heightmap tracing.

## Related

- [[Geometry Engine]]
- [[Geometry instancing]]
- [[Horizon mapping]]
- [[Image plane]]
- [[Mesh parameterization]]
- [[Micropolygon]]
- [[Newell's algorithm]]
- [[Polygon soup]]
- [[Retopology]]
- [[Schlick's approximation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Relief_mapping_(computer_graphics)