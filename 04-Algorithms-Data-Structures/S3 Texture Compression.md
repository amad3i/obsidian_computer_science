---
title: "S3 Texture Compression"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/S3_Texture_Compression"
wikipedia_categories: ["3D computer graphics", "Lossy compression algorithms", "Texture compression"]
related: ["[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D Morphable Model]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[Adobe Fuse CC]]", "[[Binary space partitioning]]"]
---

# S3 Texture Compression

S3 Texture Compression (S3TC) (sometimes also called DXTn, DXTC, or BCn) is a group of related lossy texture compression algorithms originally developed by Iourcha et al. of S3 Graphics, Ltd. for use in their Savage 3D computer graphics accelerator. The method of compression is strikingly similar to the previously published Color Cell Compression, which is in turn an adaptation of Block Truncation Coding published in the late 1970s. Unlike some image compression algorithms (e.g. JPEG), S3TC's fixed-rate data compression coupled with the single memory access (cf. Color Cell Compression and some VQ-based schemes) made it well-suited for use in compressing textures in hardware-accelerated 3D computer graphics. Its subsequent inclusion in Microsoft's DirectX 6.0 and OpenGL 1.3 (via the GL_EXT_texture_compression_s3tc extension) led to widespread adoption of the technology among hardware and software makers. While S3 Graphics is no longer a competitor in the graphics accelerator market, license fees have been levied and collected for the use of S3TC technology until October 2017, for example in game consoles and graphics cards. The wide use of S3TC has led to a de facto requirement for OpenGL drivers to support it, but the patent-encumbered status of S3TC presented a major obstacle to open source implementations, while implementation approaches which tried to avoid the patented parts existed.

## Related

- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D Morphable Model]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[Adobe Fuse CC]]
- [[Binary space partitioning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/S3_Texture_Compression