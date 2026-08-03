---
title: "Path tracing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Path_tracing"
wikipedia_categories: ["3D rendering", "Computer graphics", "Global illumination algorithms", "Monte Carlo methods", "Ray tracing (graphics)"]
related: ["[[Spatiotemporal reservoir resampling]]", "[[Ray tracing (graphics)]]", "[[Cone tracing]]", "[[Distributed ray tracing]]", "[[Non-photorealistic rendering]]", "[[Per-pixel lighting]]", "[[Screen space directional occlusion]]", "[[Stencil buffer]]", "[[Texture atlas]]", "[[2D computer graphics]]"]
---

# Path tracing

Path tracing is a rendering algorithm in computer graphics that simulates how light interacts with objects and participating media to generate realistic (physically plausible) images. It is based on earlier, more limited, ray tracing algorithms.
Path tracing is used to create photorealistic images for artistic purposes, and for applications such as architectural rendering and product design. It is also used to render frames for animated films, and visual effects for film and television. Because it can be very accurate and unbiased, it is commonly used to generate reference images when testing the quality of other rendering algorithms.
The technique uses the Monte Carlo method to compute estimates of global illumination and simulate the ways different materials reflect (or scatter), transmit, absorb, and emit light. It can incorporate simple modeling of the effects of aperture and lens (depth of field, and bokeh) and shutter speed (motion blur), or more realistic simulation of the optical components in a camera.
The algorithm works by describing illumination in a scene using the rendering equation, or light transport equation, and finding an approximate solution using Monte Carlo integration. An inefficient (but accurate) version of the algorithm can be very simple, and involves tracing a ray from the camera, allowing this ray to bounce in random directions as it hits different objects in the scene, and computing the amount of light transmitted along the path to the camera whenever the path encounters a light source. This process is repeated many times for each pixel (each repetition, with generated path and transmitted light, is called a sample), and the results are averaged. One main difference between this algorithm and standard ray tracing is that a single unbranching path is traced each time, while "Whitted-style" or "Cook-style" ray tracing recursively samples branching paths (e.g. when light is both reflected and refracted by a glass object).
More practical versions incorporate improvements such as quasi-Monte Carlo methods (techniques that distribute samples more evenly), importance sampling (take more samples of paths that are likely to transport more light), and next event estimation (allow a very limited form of branching, and sample additional paths that connect to the lights more directly).
Because path tracing uses random samples there is noise in the final image, which decreases as more samples are taken. Images commonly require many thousands of samples per pixel (spp) to reduce noise to an acceptable level, and denoising techniques (e.g. based on neural networks) are often used. Denoising is usually necessary when path tracing is used for real-time rendering in video games, because relatively few samples can be taken.
Many alternative algorithms for path tracing have been developed, although they do not always outperform more straightforward implementations. These include bidirectional path tracing (which traces paths forwards from the light source as well as backwards from the camera), Metropolis light transport, and ways of combining path tracing with photon mapping. Video games often use biased versions of path tracing to improve performance (e.g. limiting the number of bounces in each path). A family of techniques called ReSTIR has been developed that can help real-time path tracing by sharing data between nearby pixels and consecutive frames.

## Related

- [[Spatiotemporal reservoir resampling]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Path_tracing