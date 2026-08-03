---
title: "Image gradient"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Image_gradient"
wikipedia_categories: ["Computer graphics", "Image processing"]
related: ["[[Fiducial marker]]", "[[Framebuffer]]", "[[Guided filter]]", "[[Illumination (image)]]", "[[Image resolution]]", "[[Resel]]", "[[Scan line]]", "[[Visual computing]]", "[[2D computer graphics]]", "[[3D computer graphics]]"]
---

# Image gradient

An image gradient is a directional change in the intensity or color in an image. The gradient of the image is one of the fundamental building blocks in image processing. For example, the Canny edge detector uses image gradient for edge detection. In graphics software for digital image editing, the term gradient or color gradient is also used for a gradual blend of color which can be considered as an even gradation from low to high values, and seen from black to white in the images to the right. Another name for this is color progression.
Mathematically, the gradient of a two-variable function (here the image intensity function) at each image point is a 2D vector with the components given by the derivatives in the horizontal and vertical directions. At each image point, the gradient vector points in the direction of largest possible intensity increase, and the length of the gradient vector corresponds to the rate of change in that direction.
Since the intensity function of a digital image is only known at discrete points, derivatives of this function cannot be defined unless we assume that there is an underlying continuous intensity function which has been sampled at the image points. With some additional assumptions, the derivative of the continuous intensity function can be computed as a function on the sampled intensity function, i.e., the digital image. Approximations of these derivative functions can be defined at varying degrees of accuracy. The most common way to approximate the image gradient is to convolve an image with a kernel, such as the Sobel operator or Prewitt operator.
Image gradients are often utilized in maps and other visual representations of data in order to convey additional information. GIS tools use color progressions to indicate elevation and population density, among others.
In 1990s and 2000s the blue and black gradient was popular in computing as it was used in installer software.

## Related

- [[Fiducial marker]]
- [[Framebuffer]]
- [[Guided filter]]
- [[Illumination (image)]]
- [[Image resolution]]
- [[Resel]]
- [[Scan line]]
- [[Visual computing]]
- [[2D computer graphics]]
- [[3D computer graphics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Image_gradient