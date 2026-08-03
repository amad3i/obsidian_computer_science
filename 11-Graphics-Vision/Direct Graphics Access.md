---
title: "Direct Graphics Access"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Direct_Graphics_Access"
wikipedia_categories: ["Image processing", "X Window extensions"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Direct Graphics Access

Direct Graphics Access is a plug-in for the X display servers that allows client programs direct access to the frame buffer. 
Graphics hardware communicates via a chunk of memory called a frame buffer. This is an array of values that represent pixel color values on the screen. Writing the appropriate values into the frame buffer therefore allows a program to paint areas of the screen.
However, as with any shared resource, problems occur when multiple programs attempt to access the same resource, as they tend to write over each other's work. In the X Window System, this is solved by having a central display server that mediates between programs that want to draw on the screen. The display server also used to perform a lot of the drawing work, allowing programs to say Draw me a circle of this radius filled with this pattern or draw this text in this font. The X server does all this work, freeing programmers from having to write their own drawing code. Another advantage of the X architecture is that it works over a network, allowing programs on one machine to display output on the screen of another.
Direct Graphics Access allows direct access to the frame buffer and the X-server hands over control of the frame buffer to the client program and waits for the client to hand it back. This means that the client program has control of the whole screen, and so it is mostly used for full-screen video/games.

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

- Wikipedia: https://en.wikipedia.org/wiki/Direct_Graphics_Access