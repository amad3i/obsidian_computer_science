---
title: "Supersampling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Supersampling"
wikipedia_categories: ["Anti-aliasing algorithms", "Image processing"]
related: ["[[Morphological antialiasing]]", "[[Multisample anti-aliasing]]", "[[Spatial anti-aliasing]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]"]
---

# Supersampling

Supersampling or supersampling anti-aliasing (SSAA) is a spatial anti-aliasing method, i.e. a method used to remove aliasing (jagged and pixelated edges, colloquially known as "jaggies") from images rendered in computer games or other computer programs that generate imagery. Aliasing occurs because unlike real-world objects, which have continuous smooth curves and lines, a computer screen shows the viewer a large number of small squares.  These pixels all have the same size, and each one has a single color. A line can only be shown as a collection of pixels, and therefore appears jagged unless it is perfectly horizontal or vertical.  The aim of supersampling is to reduce this effect.  Color samples are taken at several instances inside the pixel (not just at the center as normal)—hence the term "supersampling"—and an average color value is calculated. This can for example be achieved by rendering the image at a much higher resolution than the one being displayed, then shrinking it to the desired size, using the extra pixels for calculation, with the result being a downsampled image with smoother transitions from one line of pixels to another along the edges of objects, but each pixel could also be supersampled using other strategies (see the Supersampling patterns section). The number of samples determines the quality of the output.

## Related

- [[Morphological antialiasing]]
- [[Multisample anti-aliasing]]
- [[Spatial anti-aliasing]]
- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Supersampling