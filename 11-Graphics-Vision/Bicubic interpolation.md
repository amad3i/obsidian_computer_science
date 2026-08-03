---
title: "Bicubic interpolation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Bicubic_interpolation"
wikipedia_categories: ["Image processing", "Multivariate interpolation"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Bicubic interpolation

In mathematics, bicubic interpolation is an extension of cubic spline interpolation (a method of applying cubic interpolation to a data set) for interpolating data points on a two-dimensional regular grid. The interpolated surface (meaning the kernel shape, not the image) is smoother than corresponding surfaces obtained by bilinear interpolation or nearest-neighbor interpolation. Bicubic interpolation can be accomplished using either Lagrange polynomials, cubic splines, or cubic convolution algorithm.
In image processing, bicubic interpolation is often chosen over bilinear or nearest-neighbor interpolation in image resampling, when speed is not an issue. In contrast to bilinear interpolation, which only takes 4 pixels (2×2) into account, bicubic interpolation considers 16 pixels (4×4). Images resampled with bicubic interpolation can have different interpolation artifacts, depending on the b and c values chosen.

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

- Wikipedia: https://en.wikipedia.org/wiki/Bicubic_interpolation