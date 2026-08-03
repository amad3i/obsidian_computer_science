---
title: "Screen space directional occlusion"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Screen_space_directional_occlusion"
wikipedia_categories: ["3D computer graphics", "Computer graphics", "Global illumination algorithms", "Shading"]
related: ["[[Per-pixel lighting]]", "[[Ray tracing (graphics)]]", "[[Rasterisation]]", "[[3D computer graphics]]", "[[Cone tracing]]", "[[Distributed ray tracing]]", "[[Fiducial marker]]", "[[Function representation]]", "[[Gooch shading]]", "[[Horizon mapping]]"]
---

# Screen space directional occlusion

Screen space directional occlusion (SSDO) is a computer graphics technique enhancing screen space ambient occlusion (SSAO) by taking direction into account to sample the ambient light (both the light coming directly at an object, as well as the light reflected off of the object directly behind it), to better approximate global illumination. SSDO was introduced by Tobias Ritschel, Thorsten Grosch, and Hans-Peter Seidel in their 2009 ACM Symposium on Interactive 3D Graphics and Games paper Approximating dynamic global illumination in image space, which describes it as extending SSAO to directional occlusion with one diffuse indirect bounce of light; later literature notes that SSDO still suffers from common screen-space artifacts such as noise and banding.

## Related

- [[Per-pixel lighting]]
- [[Ray tracing (graphics)]]
- [[Rasterisation]]
- [[3D computer graphics]]
- [[Cone tracing]]
- [[Distributed ray tracing]]
- [[Fiducial marker]]
- [[Function representation]]
- [[Gooch shading]]
- [[Horizon mapping]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Screen_space_directional_occlusion