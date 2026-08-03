---
title: "Image subtraction"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Image_subtraction"
wikipedia_categories: ["Astrophotography", "Digital photography", "Image processing", "Photographic techniques", "Photography stubs", "Technology stubs"]
related: ["[[Epsilon photography]]", "[[Film emulation]]", "[[Focus stacking]]", "[[Image editing]]", "[[Scientific Working Group – Imaging Technology]]", "[[Blend modes]]", "[[Box blur]]", "[[Curve (tonality)]]", "[[Flat-field correction]]", "[[Gigamacro]]"]
---

# Image subtraction

Image subtraction or pixel subtraction or difference imaging is an image processing technique whereby the digital numeric value of one pixel or whole image is subtracted from another image, and a new image generated from the result.  This is primarily done for one of two reasons – levelling uneven sections of an image such as half an image having a shadow on it, or detecting changes between two images.  This method can show things in the image that have changed position, brightness, color, or shape.
For this technique to work, the two images must first be spatially aligned to match features between them, and their photometric values and point spread functions must be made compatible, either by careful calibration, or by post-processing (using color mapping). The complexity of the pre-processing needed before differencing varies with the type of image, but is essential to ensure good subtraction of static features.
This is commonly used in fields such as time-domain astronomy (known primarily as difference imaging) to find objects that fluctuate in brightness or move. In automated searches for asteroids or Kuiper belt objects, the target moves and will be in one place in one image, and in another place in a reference image made an hour or day later. Thus, image processing algorithms can make the fixed stars in the background disappear, leaving only the target. Distinct families of astronomical image subtraction techniques have emerged, operating in both image space or frequency space, with distinct trade-offs in both quality of subtraction and computational cost. These algorithms lie at the heart of almost all modern (and upcoming) transient surveys, and can enable the detection of even faint supernovae embedded in bright galaxies. Nevertheless, in astronomical imaging, significant 'residuals' remain around bright, complex sources, necessitating further algorithmic steps to identify candidates (known as real-bogus classification)
The Hutchinson metric can be used to "measure of the discrepancy between two images for use in fractal image processing".

## Related

- [[Epsilon photography]]
- [[Film emulation]]
- [[Focus stacking]]
- [[Image editing]]
- [[Scientific Working Group – Imaging Technology]]
- [[Blend modes]]
- [[Box blur]]
- [[Curve (tonality)]]
- [[Flat-field correction]]
- [[Gigamacro]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Image_subtraction