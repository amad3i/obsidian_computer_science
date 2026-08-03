---
title: "Radiosity (computer graphics)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Radiosity_(computer_graphics)"
wikipedia_categories: ["3D computer graphics", "Finite element method", "Global illumination algorithms", "Heat transfer"]
related: ["[[Distributed ray tracing]]", "[[Per-pixel lighting]]", "[[Photon mapping]]", "[[Ray tracing (graphics)]]", "[[Screen space directional occlusion]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]"]
---

# Radiosity (computer graphics)

In 3D computer graphics, radiosity is an application of the finite element method to solving the rendering equation for scenes with surfaces that reflect light diffusely.  Unlike rendering methods that use Monte Carlo algorithms (such as path tracing), which handle all types of light paths, typical radiosity only account for paths (represented by the code "LD*E") which leave a light source and are reflected diffusely some number of times (possibly zero) before hitting the eye. Radiosity is a global illumination algorithm in the sense that the illumination arriving on a surface comes not just directly from the light sources, but also from other surfaces reflecting light. Radiosity is viewpoint independent, which increases the calculations involved, but makes them useful for all viewpoints.
Radiosity methods were first developed in about 1950 in the engineering field of heat transfer. They were later refined specifically for the problem of rendering computer graphics in 1984–1985 by researchers at Cornell University  and Hiroshima University.
Notable commercial radiosity engines are Enlighten by Geomerics (used for games including Battlefield 3 and Need for Speed: The Run); 3ds Max; form•Z; LightWave 3D and the Electric Image Animation System.

## Related

- [[Distributed ray tracing]]
- [[Per-pixel lighting]]
- [[Photon mapping]]
- [[Ray tracing (graphics)]]
- [[Screen space directional occlusion]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Radiosity_(computer_graphics)