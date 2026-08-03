---
title: "Pixel binning"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Pixel_binning"
wikipedia_categories: ["Image processing"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Pixel binning

Pixel binning, also known as binning, is a process image sensors of digital cameras use to combine adjacent pixels throughout an image, by summing or averaging their values, during or after readout. It improves low-light performance while still allowing for highly detailed photographs in good light.
Charge from adjacent pixels in CCD or charge-coupled device image sensors and some other image sensors can be combined during readout, increasing the line rate or frame rate.
In the context of image processing, binning is the procedure of combining clusters of adjacent pixels, throughout an image, into single pixels. For example, in 2×2 binning, an array of 4 pixels becomes a single larger pixel, reducing the number of pixels to 1/4 and halving the image resolution in each dimension. The result can be the sum, average, median, minimum, or maximum value of the cluster. Some systems use more advanced algorithms such as considering the values of nearby pixels, edge detection, self-claimed "AI", etc. to increase the perceived visual quality of the final downsized image.
This aggregation, although associated with loss of information, reduces the amount of data to be processed, facilitating analysis. The binned image has lower resolution, but the relative noise level in each pixel is generally reduced.

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

- Wikipedia: https://en.wikipedia.org/wiki/Pixel_binning