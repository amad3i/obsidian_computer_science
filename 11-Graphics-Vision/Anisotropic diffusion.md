---
title: "Anisotropic diffusion"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Anisotropic_diffusion"
wikipedia_categories: ["Image noise reduction techniques", "Image processing"]
related: ["[[Bilateral filter]]", "[[Gaussian blur]]", "[[Guided filter]]", "[[Non-local means]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]"]
---

# Anisotropic diffusion

In image processing and computer vision, anisotropic diffusion, also called Perona–Malik diffusion, is a technique aiming at reducing image noise without removing significant parts of the image content, typically edges, lines or other details that are important for the interpretation of the image.   Anisotropic diffusion resembles the process that creates a scale space, where an image generates a parameterized family of successively more and more blurred images based on a diffusion process. Each of the resulting images in this family are given as a convolution between the image and a 2D isotropic Gaussian filter, where the width of the filter increases with the parameter. This diffusion process is a linear and space-invariant transformation of the original image.  Anisotropic diffusion is a generalization of this diffusion process: it produces a family of parameterized images, but each resulting image is a combination between the original image and a filter that depends on the local content of the original image. As a consequence, anisotropic diffusion is a non-linear and space-variant transformation of the original image.
In its original formulation, presented by Perona and Malik in 1987, the space-variant filter is in fact isotropic but depends on the image content such that it approximates an impulse function close to edges and other structures that should be preserved in the image over the different levels of the resulting scale space. This formulation was referred to as anisotropic diffusion by Perona and Malik even though the locally adapted filter is isotropic, but it has also been referred to as inhomogeneous and nonlinear diffusion or Perona–Malik diffusion by other authors.  A more general formulation allows the locally adapted filter to be truly anisotropic close to linear structures such as edges or lines: it has an orientation given by the structure such that it is elongated along the structure and narrow across. Such methods are referred to as shape-adapted smoothing or coherence enhancing diffusion. As a consequence, the resulting images preserve linear structures while at the same time smoothing is made along these structures.  Both these cases can be described by a generalization of the usual diffusion equation where the diffusion coefficient, instead of being a constant scalar, is a function of image position and assumes a matrix (or tensor) value (see structure tensor).
Although the resulting family of images can be described as a combination between the original image and space-variant filters, the locally adapted filter and its combination with the image do not have to be realized in practice.  Anisotropic diffusion is normally implemented by means of an approximation of the generalized diffusion equation: each new image in the family is computed by applying this equation to the previous image. Consequently, anisotropic diffusion is an iterative process where a relatively simple set of computations is used to compute each successive image in the family and this process is continued until a sufficient degree of smoothing is obtained.

## Related

- [[Bilateral filter]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Anisotropic_diffusion