---
title: "Planar (computer graphics)"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Planar_(computer_graphics)"
wikipedia_categories: ["Amiga", "Computer graphics"]
related: ["[[Blitter object]]", "[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]"]
---

# Planar (computer graphics)

In computer graphics, planar is the method of arranging pixel data into several bitplanes of RAM. Each bit in a bitplane is related to one pixel on the screen. Unlike packed, high color, or  true color graphics, the whole dataset for an individual pixel is not in one specific location in RAM, but spread across the bitplanes that make up the display. Planar arrangement determines how pixel data is laid out in memory, not how the data for a pixel is interpreted; pixel data in a planar arrangement could encode either indexed or direct color.
This scheme originated in the early days of computer graphics. The memory chips of this era can not supply data fast enough on their own to generate a picture on a TV screen or monitor from a large framebuffer. By splitting the data up into multiple planes, each plane can be stored on a separate memory chip. These chips can then be read in parallel at a slower rate, allowing graphical display on modest hardware, like game consoles of the third and fourth generations and home computers of the 80s. The EGA video adapter on early IBM PC computers uses planar arrangement in color graphical modes for this reason. The later VGA includes one non-planar mode which sacrifices memory efficiency for more convenient access.

## Related

- [[Blitter object]]
- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Planar_(computer_graphics)