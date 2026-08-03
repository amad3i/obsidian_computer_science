---
title: "Distributed ray tracing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_ray_tracing"
wikipedia_categories: ["3D computer graphics", "Global illumination algorithms", "Ray tracing (graphics)"]
related: ["[[Ray tracing (graphics)]]", "[[Path tracing]]", "[[Per-pixel lighting]]", "[[Photon mapping]]", "[[Radiosity (computer graphics)]]", "[[Screen space directional occlusion]]", "[[Spatiotemporal reservoir resampling]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]"]
---

# Distributed ray tracing

Distributed ray tracing, also called distribution ray tracing and stochastic ray tracing, is a refinement of ray tracing that allows for the rendering of "soft" phenomena.
Conventional ray tracing uses single rays to sample many different domains.  For example, when the color of an object is calculated, ray tracing might send a single ray to each light source in the scene.  This leads to sharp shadows, since there is no way for a light source to be partially occluded (another way of saying this is that all lights are point sources and have zero area).  Conventional ray tracing also typically spawns one reflection ray and one transmission ray per intersection.  As a result, reflected and transmitted images are perfectly (and usually unrealistically) sharp.
Distributed ray tracing removes these restrictions by averaging multiple rays distributed over an interval.  For example, soft shadows can be rendered by distributing shadow rays over the light source area.  Glossy or blurry reflections and transmissions can be rendered by distributing reflection and transmission rays over a solid angle about the mirror reflection or transmission direction.  Adding "soft" phenomena to ray-traced images in this way can improve realism immensely, since the sharp phenomena rendered by conventional ray tracing are almost never seen in reality.
More advanced effects are also possible using the same framework.  For instance, depth of field can be achieved by distributing ray origins over the lens area.  In an animated scene, motion blur can be simulated by distributing rays in time.  Distributing rays in the spectrum allows for the rendering of dispersion effects, such as rainbows and prisms.
Mathematically, in order to evaluate the rendering equation, one must evaluate several integrals.  Conventional ray tracing estimates these integrals by sampling the value of the integrand at a single point in the domain, which is a very bad approximation, except for narrow domains.  Distributed ray tracing samples the integrand at many randomly chosen points and averages the results to obtain a better approximation.  It is essentially an application of the Monte Carlo method to 3D computer graphics, and for this reason is also called "stochastic ray tracing". Path tracing is a rendering technique that combines all of these integration domains into a single, high-dimensional domain and samples it in a unified way.

## Related

- [[Ray tracing (graphics)]]
- [[Path tracing]]
- [[Per-pixel lighting]]
- [[Photon mapping]]
- [[Radiosity (computer graphics)]]
- [[Screen space directional occlusion]]
- [[Spatiotemporal reservoir resampling]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_ray_tracing