---
title: "Spatiotemporal reservoir resampling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Spatiotemporal_reservoir_resampling"
wikipedia_categories: ["3D rendering", "Computer graphics", "Global illumination algorithms", "Monte Carlo methods", "Ray tracing (graphics)"]
related: ["[[Path tracing]]", "[[Ray tracing (graphics)]]", "[[Cone tracing]]", "[[Distributed ray tracing]]", "[[Non-photorealistic rendering]]", "[[Per-pixel lighting]]", "[[Screen space directional occlusion]]", "[[Stencil buffer]]", "[[Texture atlas]]", "[[2D computer graphics]]"]
---

# Spatiotemporal reservoir resampling

Spatiotemporal reservoir resampling, commonly known as ReSTIR (from "Reservoir-based SpatioTemporal Importance Resampling"), is a collection of computer graphics techniques for reusing samples during rendering. It was developed primarily to allow more realistic  lighting in real-time rendering, because relatively few rays can be traced per pixel while maintaining an acceptable frame rate. It can also be used to speed up off-line path tracing.
The first ReSTIR paper, published in 2020, provided algorithms for direct lighting, allowing scenes containing thousands of lights to be rendered in real time on a high-end GPU. Researchers later proposed versions for rendering indirect lighting (and more recently, motion blur and depth of field) and built up a framework of mathematical concepts and notation conventions that help analyze such algorithms.
A major focus of this work is removing or reducing the bias that could be introduced when samples from other pixels or frames are reused—or selectively allowing some bias in order to speed up rendering and reduce variance (visible as "noise" in the image). Versions for path tracing apply transformations called shift mappings to samples, typically reusing parts of paths closer to the light and modifying the portion closer to the camera.
ReSTIR-related papers and talks have been presented every year at the SIGGRAPH conference since 2020.
One of the first games to incorporate ReSTIR into its rendering was Cyberpunk 2077.

## Related

- [[Path tracing]]
- [[Ray tracing (graphics)]]
- [[Cone tracing]]
- [[Distributed ray tracing]]
- [[Non-photorealistic rendering]]
- [[Per-pixel lighting]]
- [[Screen space directional occlusion]]
- [[Stencil buffer]]
- [[Texture atlas]]
- [[2D computer graphics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spatiotemporal_reservoir_resampling