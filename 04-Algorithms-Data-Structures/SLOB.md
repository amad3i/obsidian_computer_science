---
title: "SLOB"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/SLOB"
wikipedia_categories: ["Linux kernel", "Linux stubs", "Memory management algorithms"]
related: ["[[SLUB (software)]]", "[[Linux Test Project]]", "[[Mm tree]]", "[[TinyLinux]]", "[[-dev-full]]", "[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]"]
---

# SLOB

The SLOB (simple list of blocks) allocator was one of three available memory allocators in the Linux kernel up to version 6.3. The other two are SLAB (slab allocator) and SLUB. The SLOB allocator is designed to require little memory for the implementation and housekeeping, for use in small systems such as embedded systems. Unfortunately, a major limitation of the SLOB allocator is that it suffers greatly from external fragmentation.
SLOB currently uses a first-fit algorithm, which uses the first available space for memory. In 2008, a reply from Linus Torvalds on a Linux mailing list was made where he suggested the use of a best-fit algorithm, which tries to find a memory block which suits needs best.  Best fit finds the smallest space which fits the required amount available, avoiding loss of performance, both by fragmentation and consolidation of memory.
By default, Linux kernel used a SLAB Allocation system until version 2.6.23, when SLUB allocation became the default. When the CONFIG_SLAB flag is disabled, the kernel falls back to using the SLOB allocator. The SLOB allocator was used in DSLinux on Nintendo DS handheld console.

## Related

- [[SLUB (software)]]
- [[Linux Test Project]]
- [[Mm tree]]
- [[TinyLinux]]
- [[-dev-full]]
- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Configuration Menu Language]]
- [[Copy Fail]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SLOB