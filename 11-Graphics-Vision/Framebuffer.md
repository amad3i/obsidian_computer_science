---
title: "Framebuffer"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Framebuffer"
wikipedia_categories: ["Computer graphics", "Computer memory", "Image processing"]
related: ["[[Fiducial marker]]", "[[Guided filter]]", "[[Illumination (image)]]", "[[Image gradient]]", "[[Image resolution]]", "[[Resel]]", "[[Scan line]]", "[[Visual computing]]", "[[2025–present global memory supply shortage]]", "[[2D computer graphics]]"]
---

# Framebuffer

A framebuffer (frame buffer, or sometimes framestore) is a portion of random-access memory (RAM) containing a bitmap that drives a video display. It is a memory buffer containing data representing all the pixels in a complete video frame. Modern video cards contain framebuffer circuitry in their cores. This circuitry helps convert an in-memory bitmap into a video signal that can be displayed on a computer monitor.
In computing, a screen buffer is a part of computer memory used by a computer application for the representation of the content to be shown on the computer display. The screen buffer may also be called the video buffer, the regeneration buffer, or regen buffer for short.  The phrase "screen buffer” refers to a logical function, while video memory refers to a hardware storage location. In particular, the screen buffer may be placed in the main RAM, the video memory, or some other hardware location.
To reduce latency and avoid screen tearing, multiple frames can be buffered, and this technique is called multiple buffering. When this is so, at any time, only one frame would be visible, and the others would not be. The currently invisible frames are located in the off-screen buffer.
The information in the buffer typically consists of color values for every pixel to be shown on the display. Color values are commonly stored in 1-bit binary (monochrome), 4-bit palettized, 8-bit palettized, 16-bit high color and 24-bit true color formats. An additional alpha channel is sometimes used to retain information about pixel transparency. The total amount of memory required for the framebuffer depends on the resolution of the output signal, and on the color depth or palette size.

## Related

- [[Fiducial marker]]
- [[Guided filter]]
- [[Illumination (image)]]
- [[Image gradient]]
- [[Image resolution]]
- [[Resel]]
- [[Scan line]]
- [[Visual computing]]
- [[2025–present global memory supply shortage]]
- [[2D computer graphics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Framebuffer