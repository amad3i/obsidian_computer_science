---
title: "Adaptive tile refresh"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Adaptive_tile_refresh"
wikipedia_categories: ["Commander Keen", "Computer graphics", "Video game graphics"]
related: ["[[Glossary of computer graphics]]", "[[2.5D]]", "[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Bitmap textures]]"]
---

# Adaptive tile refresh

Adaptive tile refresh is a computer graphics technique for side-scrolling video games. It was most famously used by id Software's John Carmack in games such as Commander Keen to compensate for the poor graphics performance of PCs in the early 1990s. Its principal innovation is a novel use of several EGA hardware features to perform the scrolling in hardware. The technique is named for its other aspect, the tracking of moved graphical elements in order to minimize the amount of redrawing required in every frame. Together, the combination saves the processing time that would be otherwise required for redrawing the entire screen. Carmack designed the software engine based on a scrolling display for large images from the 1970s.
The IBM PC graphics generation previous to EGA is CGA, which lacks features for smooth horizontal scrolling in hardware. Therefore, CGA scrolling is usually done in software, by redrawing the entire screen for every frame, which early IBM PC systems lack the performance to do for full-screen animation. Adaptive tile refresh minimizes the computing power required for sidescrolling games to be within the reach of contemporary hardware. This works by flagging bitmap tiles and redrawing only the graphics on the screen that actually update.

## Related

- [[Glossary of computer graphics]]
- [[2.5D]]
- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Bitmap textures]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Adaptive_tile_refresh