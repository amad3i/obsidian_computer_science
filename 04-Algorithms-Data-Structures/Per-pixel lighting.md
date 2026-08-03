---
title: "Per-pixel lighting"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Per-pixel_lighting"
wikipedia_categories: ["3D computer graphics", "Computer graphics", "Global illumination algorithms", "Shading"]
related: ["[[Ray tracing (graphics)]]", "[[Screen space directional occlusion]]", "[[Rasterisation]]", "[[3D computer graphics]]", "[[Cone tracing]]", "[[Distributed ray tracing]]", "[[Fiducial marker]]", "[[Function representation]]", "[[Gooch shading]]", "[[Horizon mapping]]"]
---

# Per-pixel lighting

In computer graphics, per-pixel lighting refers to any technique for lighting an image or scene that calculates illumination for each pixel on a rendered image. This is in contrast to other popular methods of lighting such as vertex lighting, which calculates illumination at each vertex of a 3D model and then interpolates the resulting values over the model's faces to calculate the final per-pixel color values.
Per-pixel lighting is commonly used with techniques, such as blending, alpha blending, alpha to coverage, anti-aliasing, texture filtering, clipping, hidden-surface determination, Z-buffering, stencil buffering, shading, mipmapping, normal mapping, bump mapping, displacement mapping, parallax mapping, shadow mapping, specular mapping, shadow volumes, high-dynamic-range rendering, ambient occlusion (screen space ambient occlusion, screen space directional occlusion, ray-traced ambient occlusion), ray tracing, global illumination, and tessellation. Each of these techniques provides some additional data about the surface being lit or the scene and light sources that contributes to the final look and feel of the surface.
Most modern video game engines implement lighting using per-pixel techniques instead of vertex lighting to achieve increased detail and realism.  The id Tech 4 engine, used to develop such games as Brink and Doom 3, was one of the first game engines to implement a completely per-pixel shading engine.  All versions of the CryENGINE, Frostbite Engine, and Unreal Engine, among others, also implement per-pixel shading techniques.
Deferred shading is a recent development in per-pixel lighting notable for its use in the Frostbite Engine and Battlefield 3. Deferred shading techniques are capable of rendering potentially large numbers of small lights inexpensively (other per-pixel lighting approaches require full-screen calculations for each light in a scene, regardless of size).

## Related

- [[Ray tracing (graphics)]]
- [[Screen space directional occlusion]]
- [[Rasterisation]]
- [[3D computer graphics]]
- [[Cone tracing]]
- [[Distributed ray tracing]]
- [[Fiducial marker]]
- [[Function representation]]
- [[Gooch shading]]
- [[Horizon mapping]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Per-pixel_lighting