---
title: "Stencil buffer"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Stencil_buffer"
wikipedia_categories: ["3D rendering", "Computer graphics"]
related: ["[[Non-photorealistic rendering]]", "[[Path tracing]]", "[[Spatiotemporal reservoir resampling]]", "[[Texture atlas]]", "[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]"]
---

# Stencil buffer

A stencil buffer is an extra data buffer, in addition to the color buffer and Z-buffer, found on modern graphics hardware. The buffer is per pixel and works on integer values, usually with a depth of one byte per pixel. The Z-buffer and stencil buffer often share the same area in the RAM of the graphics hardware.
In the simplest case, the stencil buffer is used to limit the area of rendering (stenciling). More advanced usage of the stencil buffer makes use of the strong connection between the Z-buffer and the stencil buffer in the rendering pipeline.  For example, stencil values can be automatically increased/decreased for every pixel that fails or passes the depth test.
The simple combination of depth test and stencil modifiers make a vast number of effects possible (such as stencil shadow volumes, Two-Sided Stencil, compositing, decaling, dissolves, fades, swipes, silhouettes, outline drawing, or highlighting of intersections between complex primitives) though they often require several rendering passes and, therefore, can put a heavy load on the graphics hardware.
The most typical application is still to add shadows to 3D applications. It is also used for planar reflections.
Other rendering techniques, such as portal rendering, use the stencil buffer in other ways; for example, it can be used to find the area of the screen obscured by a portal and re-render those pixels correctly.
The stencil buffer and its modifiers can be accessed in computer graphics by using APIs like OpenGL, Direct3D, Vulkan or Metal.

## Related

- [[Non-photorealistic rendering]]
- [[Path tracing]]
- [[Spatiotemporal reservoir resampling]]
- [[Texture atlas]]
- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stencil_buffer