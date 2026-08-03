---
title: "Bilateral filter"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Bilateral_filter"
wikipedia_categories: ["Image noise reduction techniques", "Image processing"]
related: ["[[Anisotropic diffusion]]", "[[Gaussian blur]]", "[[Guided filter]]", "[[Non-local means]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]"]
---

# Bilateral filter

A bilateral filter is a non-linear, edge-preserving, and noise-reducing smoothing filter for images. It replaces the intensity of each pixel with a weighted average of intensity values from nearby pixels. This weight can be based on a Gaussian distribution. Crucially, the weights depend not only on Euclidean distance of pixels, but also on the radiometric differences (e.g., variations in color intensity or depth). This dual dependency preserves sharp edges while suppressing noise.

## Related

- [[Anisotropic diffusion]]
- [[Gaussian blur]]
- [[Guided filter]]
- [[Non-local means]]
- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bilateral_filter