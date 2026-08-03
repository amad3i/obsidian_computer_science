---
title: "Video overlay"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Video_overlay"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Video overlay

Video overlay is any technique used to display a video window on a computer display while bypassing the chain of CPU to graphics card to computer monitor. This is done in order to speed up the video display, and it is commonly used, for example, by TV tuner cards and early 3D graphics accelerator cards. The term is also used to describe the annotation or inclusion of interactivity on online videos, such as overlay advertising (mid-roll overlay).
Various methods to achieve video overlay are in use:

A video overlay device can be connected between the graphics card analog VGA output and the monitor's input, forming a "VGA passthrough". The device modifies the VGA signal and inserts the analog video signal overlay into the picture; the rest of the screen is filled by the signal coming from the graphics card. The driver software informs the video overlay device about the desired position of the video window on screen. Because of the much greater processing power of modern graphics cards, and the awkwardness of adding an additional analog hardware signal processing path, this method is now little used.
Some video overlay devices write the digital video signal directly into the graphics card's video memory or provide it to the graphics card's RAMDAC.
Hardware overlay is a technique implemented by most modern graphics cards that allows an application to write to a dedicated part of video memory, rather than to the part shared by all applications. In this way, clipping, moving and scaling of the image can be performed by the graphics hardware rather than by the CPU in software. Some solid state video recording systems now include a hardware overlay, which uses dedicated video processing hardware built into the main processor (for example the Texas Instruments DM355) to combine each frame of video with an area of memory configured as a frame buffer which is used to store the graphics.

Overlay advertising is a technique used by online video producers to monetize video content through using an overlay layer to deliver and display an ad unit.  This can be in the form of a video advertisement, hypervideo a product placement or a contextual link, clickable graphic or text that provides information related to the content of the video and/or the target of the link being placed.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Video_overlay