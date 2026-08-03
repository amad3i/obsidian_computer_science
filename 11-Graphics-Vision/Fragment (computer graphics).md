---
title: "Fragment (computer graphics)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Fragment_(computer_graphics)"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Fragment (computer graphics)

In computer graphics, a fragment is the data necessary to generate a single pixel's worth of a drawing primitive in the frame buffer.  
These data may include, but are not limited to:

raster position
depth
interpolated attributes (color, texture coordinates, etc.)
stencil
alpha
window ID
In multisampled rendering, a fragment also carries sample-coverage information, and a single shader result may be shared across the covered samples of a pixel.
As a scene is drawn, drawing primitives (the basic elements of graphics output, such as points, lines, circles, text etc.) are rasterized into fragments which are textured and combined with the existing frame buffer. How a fragment is combined with the data already in the frame buffer depends on various settings. In a typical case, a fragment may be discarded if it is further away than the pixel which is already at that location (according to the depth buffer). If it is nearer than the existing pixel, it may replace what is already there, or, if alpha blending is in use, the pixel's color may be replaced with a mixture of the fragment's color and the pixel's existing color, as in the case of drawing a translucent object.
In general, a fragment can be thought of as the data needed to shade the pixel, plus the data needed to test whether the fragment survives to become a pixel (depth, alpha, stencil, scissor, window ID, etc.). Shading a fragment is done through a fragment shader (or pixel shaders in Direct3D).
In computer graphics, a fragment is not necessarily opaque, and could contain an alpha value specifying its degree of transparency. The alpha is typically normalized to the range of [0, 1], with 0 denotes totally transparent and 1 denotes totally opaque. If the fragment is not totally opaque, then part of its background object could show through, which is known as alpha blending.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fragment_(computer_graphics)