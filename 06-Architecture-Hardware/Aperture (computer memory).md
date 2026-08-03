---
title: "Aperture (computer memory)"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Aperture_(computer_memory)"
wikipedia_categories: ["Computer architecture", "Computer memory", "Computer storage stubs"]
related: ["[[Cache hierarchy]]", "[[Cache pollution]]", "[[Cache-only memory architecture]]", "[[Computational RAM]]", "[[MCDRAM]]", "[[Memory ordering]]", "[[Random-access memory]]", "[[2025–present global memory supply shortage]]", "[[Abstraction layer]]", "[[Address space]]"]
---

# Aperture (computer memory)

In computing, an aperture is a portion of physical address space (i.e. physical memory) that is associated with a particular peripheral device or a memory unit. Apertures may reach external devices such as ROM or RAM chips, or internal memory on the CPU itself.
Typically, a memory device attached to a computer accepts addresses starting at zero, and so a system with more than one such device would have ambiguous addressing. To resolve this, the memory logic will contain several aperture selectors, each containing a range selector and an interface to one of the memory devices. 
The set of selector address ranges of the apertures are disjoint. When the CPU presents a physical address within the range recognized by an aperture, the aperture unit routes the request (with the address remapped to a zero base) to the attached device. Thus, apertures form a layer of address translation below the level of the usual virtual-to-physical mapping.

## Related

- [[Cache hierarchy]]
- [[Cache pollution]]
- [[Cache-only memory architecture]]
- [[Computational RAM]]
- [[MCDRAM]]
- [[Memory ordering]]
- [[Random-access memory]]
- [[2025–present global memory supply shortage]]
- [[Abstraction layer]]
- [[Address space]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Aperture_(computer_memory)