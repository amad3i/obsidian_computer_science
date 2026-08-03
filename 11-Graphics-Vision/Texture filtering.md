---
title: "Texture filtering"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Texture_filtering"
wikipedia_categories: ["Computer graphics", "Texture filtering"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Texture filtering

In computer graphics, texture filtering or texture smoothing is the method used to determine the texture color for a texture mapped pixel, using the colors of nearby texels (ie. pixels of the texture).
Filtering describes how a texture is applied at many different shapes, size, angles and scales. Depending on the chosen filter algorithm, the result will show varying degrees of blurriness, detail, spatial aliasing, temporal aliasing and blocking. Depending on the circumstances, filtering can be performed in software (such as a software rendering package) or in hardware, eg. with either real time or GPU accelerated rendering circuits, or in a mixture of both. For most common interactive graphical applications, modern texture filtering is performed by dedicated hardware which optimizes memory access through memory cacheing and pre-fetch, and implements a selection of algorithms available to the user and developer.
There are two main categories of texture filtering: magnification filtering and minification filtering. Depending on the situation, texture filtering is either a type of reconstruction filter where sparse data is interpolated to fill gaps (magnification), or a type of anti-aliasing (AA) where texture samples exist at a higher frequency than required for the sample frequency needed for texture fill (minification).
There are many methods of texture filtering, which make different trade-offs between computational complexity, memory bandwidth and image quality.

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

- Wikipedia: https://en.wikipedia.org/wiki/Texture_filtering