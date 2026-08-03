---
title: "Fillrate"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Fillrate"
wikipedia_categories: ["Computer graphics", "Computer graphics stubs"]
related: ["[[4D reconstruction]]", "[[Color clock]]", "[[Colour banding]]", "[[Czekanowski distance]]", "[[Depth peeling]]", "[[Device-independent pixel]]", "[[Drop shadow]]", "[[Glyph (data visualization)]]", "[[Gooch shading]]", "[[Himetric]]"]
---

# Fillrate

In computer graphics, a video card's pixel fillrate refers to the number of pixels that can be rendered on the screen and written to video memory in one second. Pixel fillrates are given in megapixels per second or in gigapixels per second (in the case of newer cards), and are obtained by multiplying the number of render output units (ROPs) by the clock frequency of the graphics processing unit (GPU) of a video card. 
A similar concept, texture fillrate, refers to the number of texture map elements (texels) the GPU can map to pixels in one second. Texture fillrate is obtained by multiplying the number of texture mapping units (TMUs) by the clock frequency of the GPU. Texture fillrates are given in mega or gigatexels per second.
However, there is no full agreement on how to calculate and report fillrates. Another possible method is to multiply the number of pixel pipelines by the GPU's clock frequency.
The results of these multiplications correspond to a theoretical number. The actual fillrate depends on many other factors. In the past, the fillrate has been used as an indicator of performance by video card manufacturers such as ATI and NVIDIA, however, the importance of the fillrate as a measurement of performance has declined as the bottleneck in graphics applications has shifted. For example, today, the number and speed of unified shader processing units has gained attention. Although fillrate doesn't provide a substantial bottleneck in games, it can still provide a bottleneck for certain parts of the game, for example applying a gaussian blur can be bottlenecked by fillrate.
Scene complexity can be increased by overdrawing, which happens when an object is drawn to the frame buffer, and another object (such as a wall) is then drawn on top of it, covering it up. The time spent drawing the first object is thus wasted because it is not visible. When a sequence of scenes is extremely complex (many pixels have to be drawn for each scene), the frame rate for the sequence may drop. When designing graphics intensive applications, one can determine whether the application is fillrate-limited (or shader limited) by seeing if the frame rate increases dramatically when the application runs at a lower resolution or in a smaller window. Although this is not a full-proof method, modern videogame engines can dynamically reduce the level-of-detail required and thereby reducing fillrate-limited applications. The best way to find fillrate bottlenecks is to use GPU vendor software like NVIDIA Nsight Graphics, AMD Radeon GPU Profile and the Intel Graphics Performance Analyzers.

## Related

- [[4D reconstruction]]
- [[Color clock]]
- [[Colour banding]]
- [[Czekanowski distance]]
- [[Depth peeling]]
- [[Device-independent pixel]]
- [[Drop shadow]]
- [[Glyph (data visualization)]]
- [[Gooch shading]]
- [[Himetric]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fillrate