---
title: "Generalised Hough transform"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Generalised_Hough_transform"
wikipedia_categories: ["Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Generalised Hough transform

The generalized Hough transform (GHT), introduced by Dana H. Ballard in 1981, is the modification of the Hough transform using the principle of template matching. The Hough transform was initially developed to detect analytically defined shapes (e.g., line, circle, ellipse etc.). In these cases, we have knowledge of the shape and aim to find out its location and orientation in the image. This modification enables the Hough transform to be used to detect an arbitrary object described with its model.
The problem of finding the object (described with a model) in an image can be solved by finding the model's position in the image. With the generalized Hough transform, the problem of finding the model's position is transformed to a problem of finding the transformation's parameter that maps the model into the image. Given the value of the transformation's parameter, the position of the model in the image can be determined.
The original implementation of the GHT used edge information to define a mapping from orientation of an edge point to a reference point of the shape. In the case of a binary image where pixels can be either black or white, every black pixel of the image can be a black pixel of the desired pattern thus creating a locus of reference points in the Hough space. Every pixel of the image votes for its corresponding reference points. The maximum points of the Hough space indicate possible reference points of the pattern in the image. This maximum can be found by scanning the Hough space or by solving a relaxed set of equations, each of them corresponding to a black pixel.

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

- Wikipedia: https://en.wikipedia.org/wiki/Generalised_Hough_transform