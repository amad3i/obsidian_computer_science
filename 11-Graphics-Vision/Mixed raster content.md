---
title: "Mixed raster content"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Mixed_raster_content"
wikipedia_categories: ["Computer graphics", "Computer graphics stubs", "ISO/IEC standards", "ITU-T recommendations", "JPEG"]
related: ["[[4D reconstruction]]", "[[Color clock]]", "[[Colour banding]]", "[[Czekanowski distance]]", "[[Depth peeling]]", "[[Device-independent pixel]]", "[[Drop shadow]]", "[[Fillrate]]", "[[Glyph (data visualization)]]", "[[Gooch shading]]"]
---

# Mixed raster content

Mixed raster content (MRC) is a method for compressing images that contain both binary-compressible text and continuous-tone components, using image segmentation methods to improve the level of compression and the quality of the rendered image. By separating the image into components with different compressibility characteristics, the most efficient and accurate compression algorithm for each component can be applied.
MRC-compressed images are typically packaged into a hybrid file format such as DjVu and sometimes PDF. This allows for multiple images, and the instructions to properly render and reassemble them, to be stored within a single file.
Some image scanners optionally support MRC when scanning to PDF. A typical manual states that without MRC, the image is generated in a single process, with text and graphics not distinguished. With MRC, separate processes are used for text, graphics, and other elements, producing clearer graphics and sharper text, at the price of slightly slower processing. MRC is recommended to optimise the scanning of documents with harder-to-read text or lower-quality graphics. MRC can also reduce the size of the scanned file, though higher compression using JBIG2 can sometimes lead to character substitution errors in scanned documents.

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

- Wikipedia: https://en.wikipedia.org/wiki/Mixed_raster_content