---
title: "T-vertices"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/T-vertices"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# T-vertices

T-vertices is a term used in computer graphics to describe a problem that can occur during mesh refinement or mesh simplification.  The most common case occurs in naive implementations of continuous level of detail, where a finer-level mesh is "sewn" together with a coarser-level mesh by simply aligning the finer vertices on the edges of the coarse polygons.  The result is a continuous mesh, however due to the nature of the z-buffer and certain lighting algorithms such as Gouraud shading, visual artifacts can often be detected.

Some modeling algorithms such as subdivision surfaces will fail when a model contains T-vertices.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/T-vertices