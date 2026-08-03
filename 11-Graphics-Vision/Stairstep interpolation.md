---
title: "Stairstep interpolation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Stairstep_interpolation"
wikipedia_categories: ["Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Stairstep interpolation

In the field of  image processing, stairstep interpolation is a widely employed method technique for interpolating pixels after enlarging an image. The fundamental concept is to interpolate multiple times, in small increments, using any interpolation algorithm that is better than nearest-neighbor interpolation such as; bilinear interpolation, and bicubic interpolation. A common scenario is to interpolate an image by using a bicubic interpolation which increases the image size by no more than 10% (110% of the original size) at a time until the desired size is reached.
Fred Miranda, a developer, popularized this method by creating and developing several Photoshop plug-ins that incorporate this technique.

## Related

- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]
- [[Atkinson dithering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stairstep_interpolation