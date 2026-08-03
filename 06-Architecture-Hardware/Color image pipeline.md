---
title: "Color image pipeline"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Color_image_pipeline"
wikipedia_categories: ["Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Color image pipeline

An image pipeline or video pipeline is the set of components commonly used between an image source (such as a camera, a scanner, or the rendering engine in a computer game), and an image renderer (such as a television set, a computer screen, a computer printer or cinema screen), or for performing any intermediate digital image processing consisting of two or more separate processing blocks. An image/video pipeline may be implemented as computer software, in a digital signal processor, on an FPGA, or as fixed-function ASIC. In addition, analog circuits can be used to do many of the same functions.
Typical components include image sensor corrections (including debayering or applying a Bayer filter), noise reduction, image scaling, gamma correction, image enhancement, colorspace conversion (between formats such as RGB, YUV or YCbCr), chroma subsampling, framerate conversion, image compression/video compression (such as JPEG), and computer data storage/data transmission.
Typical goals of an imaging pipeline may be perceptually pleasing end-results, colorimetric precision, a high degree of flexibility, low cost/low CPU utilization/long battery life, or reduction in bandwidth/file size.
Some functions may be algorithmically linear. Mathematically, those elements can be connected in any order without changing the end-result. As digital computers use a finite approximation to numerical computing, this is in practice not true. Other elements may be non-linear or time-variant. For both cases, there is often one or a few sequences of components that makes sense for optimum precision and minimum hardware-cost/CPU-load.

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

- Wikipedia: https://en.wikipedia.org/wiki/Color_image_pipeline