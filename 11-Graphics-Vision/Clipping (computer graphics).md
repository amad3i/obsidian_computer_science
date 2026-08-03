---
title: "Clipping (computer graphics)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Clipping_(computer_graphics)"
wikipedia_categories: ["Clipping (computer graphics)", "Computer graphic artifacts", "Computer graphics"]
related: ["[[Clipmap]]", "[[Colour banding]]", "[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]"]
---

# Clipping (computer graphics)

Clipping, in the context of computer graphics, is a method to selectively enable or disable rendering operations within a defined region of interest. Mathematically, clipping can be described using the terminology of constructive geometry. A rendering algorithm only draws pixels in the intersection between the clip region and the scene model. Lines and surfaces outside the view volume (aka. frustum) are removed.
Clip regions are commonly specified to improve render performance. Pixels that will be drawn are said to be within the clip region. Pixels that will not be drawn are outside the clip region. More informally, pixels that will not be drawn are said to be "clipped."

## Related

- [[Clipmap]]
- [[Colour banding]]
- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Clipping_(computer_graphics)