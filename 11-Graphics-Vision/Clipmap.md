---
title: "Clipmap"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Clipmap"
wikipedia_categories: ["Clipping (computer graphics)", "Computer graphics", "Id Tech", "Texture mapping"]
related: ["[[Clipping (computer graphics)]]", "[[Texture mapping]]", "[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]"]
---

# Clipmap

In computer graphics, clipmapping is a method of clipping a mipmap to a subset of data pertinent to the geometry being displayed. The technique was introduced by Christopher C. Tanner, Christopher J. Migdal, and Michael T. Jones as a "virtual mipmap" for caching arbitrarily large textures in finite physical memory for real-time rendering. This is useful for loading as little data as possible when memory is limited, such as on a graphics processing unit. For terrain rendering, the idea was adapted into geometry clipmaps, which use nested regular grids centered on the viewer and update them incrementally as the viewpoint moves. The technique is used for LODing in NVIDIA’s implementation of voxel cone tracing. The high-resolution levels of the mipmapped scene representation are clipped to a region near the camera, while lower resolution levels are clipped further away.

## Related

- [[Clipping (computer graphics)]]
- [[Texture mapping]]
- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Clipmap