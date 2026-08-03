---
title: "Colour banding"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Colour_banding"
wikipedia_categories: ["Computer graphic artifacts", "Computer graphics", "Computer graphics stubs", "Visual artifacts"]
related: ["[[4D reconstruction]]", "[[Alpha to coverage]]", "[[Clipping (computer graphics)]]", "[[Color clock]]", "[[Czekanowski distance]]", "[[Depth peeling]]", "[[Device-independent pixel]]", "[[Drop shadow]]", "[[Fillrate]]", "[[Glyph (data visualization)]]"]
---

# Colour banding

Colour banding is a subtle form of posterisation in digital images, caused by the colour of each pixel being rounded to the nearest of the digital colour levels. While posterisation is often done for artistic effect, colour banding is an undesired artefact. In 24-bit colour modes, 8 bits per channel is usually considered sufficient to render images in Rec. 709 or sRGB. However the eye can see the difference between the colour levels, especially when there is a sharp border between two large areas of adjacent colour levels. This will happen with gradual gradients (like sunsets, dawns or clear blue skies), and also when blurring an image a large amount.
Colour banding is more noticeable with fewer bits per pixel (BPP) at 16–256 colours (4–8 BPP), where there are fewer shades with a larger difference between them. The appearance of colour banding is exaggerated by the Mach bands effect.
Possible solutions include the introduction of dithering and increasing the number of bits per colour channel.
Because the banding comes from limitations in the presentation of the image, blurring the image does not fix this unless the image BPP is higher than the original.

## Related

- [[4D reconstruction]]
- [[Alpha to coverage]]
- [[Clipping (computer graphics)]]
- [[Color clock]]
- [[Czekanowski distance]]
- [[Depth peeling]]
- [[Device-independent pixel]]
- [[Drop shadow]]
- [[Fillrate]]
- [[Glyph (data visualization)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Colour_banding