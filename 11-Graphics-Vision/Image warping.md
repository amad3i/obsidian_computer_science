---
title: "Image warping"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Image_warping"
wikipedia_categories: ["Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Image warping

Image warping is the process of digitally manipulating an image such that any shapes portrayed in the image have been significantly distorted. Warping may be used for correcting image distortion as well as for creative purposes (e.g., morphing). The same techniques are equally applicable to video.
While an image can be transformed in various ways, pure warping means that points are mapped to points without changing the colors. This can be based mathematically on any function from (part of) the plane to the plane. If the function is injective the original can be reconstructed. If the function is a bijection any image can be inversely transformed.
Some methods are:

Images may be distorted through simulation of optical aberrations.
Images may be viewed as if they had been projected onto a curved or mirrored surface. (This is often seen in ray traced images.)
Images can be partitioned into image polygons and each polygon distorted.
Images can be distorted using morphing.
The most obvious approach to transforming a digital image is the forward mapping.  This applies the transform directly to the source image, typically generating unevenly-spaced points that will then be interpolated to generate the required regularly-spaced pixels.  However, for injective transforms reverse mapping is also available.  This applies the inverse transform to the target pixels to find the unevenly-spaced locations in the source image that contribute to them.  Estimating them from source image pixels will require interpolation of the source image.
To work out what kind of warping has taken place between consecutive images, one can use optical flow estimation techniques.

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

- Wikipedia: https://en.wikipedia.org/wiki/Image_warping