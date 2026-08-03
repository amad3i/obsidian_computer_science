---
title: "Graphics address remapping table"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Graphics_address_remapping_table"
wikipedia_categories: ["Computer graphics", "Graphics hardware", "Peripheral Component Interconnect"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Graphics address remapping table

The graphics address remapping table (GART), also known as the graphics aperture remapping table, or graphics translation table (GTT), is an I/O memory management unit (IOMMU) used by Accelerated Graphics Port (AGP) and PCI Express (PCIe) graphics cards. The GART allows the graphics card direct memory access (DMA) to the host system memory, through which buffers of textures, polygon meshes and other data are loaded. AMD later reused the same mechanism for I/O virtualization with other peripherals including disk controllers and network adapters.
A GART is used as a means of data exchange between the main memory and video memory through which buffers (i.e. paging/swapping) of textures, polygon meshes and other data are loaded, but can also be used to expand the amount of video memory available for systems with only integrated or shared graphics (i.e. no discrete or inbuilt graphics processor), such as Intel HD Graphics processors.  However, this type of memory (expansion) remapping has a caveat that affects the entire system: specifically, any GART, pre-allocated memory becomes pooled and cannot be utilised for any other purposes but graphics memory and display rendering.
Since PCI Express, the GART is extended to the GTT (Graphics Translation Table), which act as a buffer or cache between system memory and graphics card, and in PCI Express, the GTT buffer size is changeable by the GPU driver.

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

- Wikipedia: https://en.wikipedia.org/wiki/Graphics_address_remapping_table