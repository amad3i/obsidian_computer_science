---
title: "Photon mapping"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Photon_mapping"
wikipedia_categories: ["3D computer graphics", "Global illumination algorithms", "Infographics"]
related: ["[[Cutaway drawing]]", "[[Distributed ray tracing]]", "[[Per-pixel lighting]]", "[[Radiosity (computer graphics)]]", "[[Ray tracing (graphics)]]", "[[Screen space directional occlusion]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]"]
---

# Photon mapping

In computer graphics, photon mapping is a two-pass global illumination rendering algorithm developed by Henrik Wann Jensen between 1995 and 2001 that approximately solves the rendering equation for integrating light radiance at a given point in space. Rays from the light source (like photons) and rays from the camera are traced independently until some termination criterion is met, then they are connected in a second step to produce a radiance value. The algorithm is used to realistically simulate the interaction of light with different types of objects (similar to other photorealistic rendering techniques). Specifically, it is capable of simulating the refraction of light through a transparent substance such as glass or water (including caustics), diffuse interreflection between illuminated objects, the subsurface scattering of light in translucent materials, and some of the effects caused by particulate matter such as smoke or water vapor.  Photon mapping can also be extended to more accurate simulations of light, such as spectral rendering. Progressive photon mapping (PPM) starts with ray tracing and then adds more and more photon mapping passes to provide a progressively more accurate render.
Unlike path tracing, bidirectional path tracing, volumetric path tracing, and Metropolis light transport, photon mapping is a "biased" rendering algorithm, which means that averaging infinitely many renders of the same scene using this method does not converge to a correct solution to the rendering equation.  However, it is a consistent method, and the accuracy of a render can be increased by increasing the number of photons. As the number of photons approaches infinity, a render will get closer and closer to the solution of the rendering equation.

## Related

- [[Cutaway drawing]]
- [[Distributed ray tracing]]
- [[Per-pixel lighting]]
- [[Radiosity (computer graphics)]]
- [[Ray tracing (graphics)]]
- [[Screen space directional occlusion]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Photon_mapping