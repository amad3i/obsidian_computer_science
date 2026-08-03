---
title: "9-slice scaling"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/9-slice_scaling"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]", "[[Blitter object]]"]
---

# 9-slice scaling

9-slice scaling (also known as Scale 9 grid, 9-slicing or 9-patch) is a 2D image resizing technique to proportionally scale an image by splitting it into a grid of nine parts.
The key idea is to prevent image scaling distortion by protecting the pixels defined in 4 parts (corners) of the image and scaling or repeating the pixels in the other 5 parts. 
A variation of the concept, the 3-slice scaling, consists of a grid of 3 parts in which only the pixels in 2 parts (the edges) are protected, and the pixels in the middle part are repeated.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]
- [[Blitter object]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/9-slice_scaling