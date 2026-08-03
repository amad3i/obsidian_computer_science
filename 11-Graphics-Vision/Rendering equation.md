---
title: "Rendering equation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Rendering_equation"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Rendering equation

In computer graphics, the rendering equation is an integral equation that expresses the amount of light leaving a point on a surface as the sum of emitted light and reflected light. It was independently introduced into computer graphics by David Immel et al. and James Kajiya in 1986. The equation is important in the theory of physically based rendering, describing the relationships between the bidirectional reflectance distribution function (BRDF) and the radiometric quantities used in rendering.
The rendering equation is defined at every point on every surface in the scene being rendered, including points hidden from the camera. The incoming light quantities on the right side of the equation usually come from the left (outgoing) side at other points in the scene (ray casting can be used to find these other points). The radiosity rendering method solves a discrete approximation of this system of equations. In distributed ray tracing, the integral on the right side of the equation may be evaluated using Monte Carlo integration by randomly sampling possible incoming light directions. Path tracing improves and simplifies this method.
The rendering equation can be extended to handle effects such as fluorescence (in which some absorbed energy is re-emitted at different wavelengths) and can support  transparent and translucent materials by using a bidirectional scattering distribution function (BSDF) in place of a BRDF. The theory of path tracing sometimes uses a path integral (integral over possible paths from a light source to a point) instead of the integral over possible incoming directions.

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

- Wikipedia: https://en.wikipedia.org/wiki/Rendering_equation