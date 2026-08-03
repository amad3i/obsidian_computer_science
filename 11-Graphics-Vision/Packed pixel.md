---
title: "Packed pixel"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Packed_pixel"
wikipedia_categories: ["Computer graphics", "Computer graphics stubs"]
related: ["[[4D reconstruction]]", "[[Color clock]]", "[[Colour banding]]", "[[Czekanowski distance]]", "[[Depth peeling]]", "[[Device-independent pixel]]", "[[Drop shadow]]", "[[Fillrate]]", "[[Glyph (data visualization)]]", "[[Gooch shading]]"]
---

# Packed pixel

In packed pixel or chunky framebuffer organization, the bits defining each pixel are clustered and stored consecutively. For example, if there are 16 bits per pixel, each pixel is represented in two consecutive (contiguous) 8-bit bytes in the framebuffer.  If there are 4 bits per pixel, each framebuffer byte defines two pixels, one in each nibble.  The latter example is as opposed to storing a single 4-bit pixel in a byte, leaving 4 bits of the byte unused. If a pixel has more than one channel, the channels are interleaved when using packed pixel organization.
Packed pixel displays were common on early microcomputer system that shared a single main memory for both the central processing unit (CPU) and display driver. In such systems, memory was normally accessed a byte at a time, so by packing the pixels, the display system could read out several pixels worth of data in a single read operation.
Packed pixel is one of two major ways to organize graphics data in memory, the other being planar organization, where each pixel is made of individual bits stored in their own plane. For a 4-bit color value, memory would be organized as four screen-sized planes of one bit each and a single pixel's value built up by selecting the appropriate bit from each plane. Planar organization has the advantage that the data can be accessed in parallel, and is used when memory bandwidth is an issue.

## Related

- [[4D reconstruction]]
- [[Color clock]]
- [[Colour banding]]
- [[Czekanowski distance]]
- [[Depth peeling]]
- [[Device-independent pixel]]
- [[Drop shadow]]
- [[Fillrate]]
- [[Glyph (data visualization)]]
- [[Gooch shading]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Packed_pixel