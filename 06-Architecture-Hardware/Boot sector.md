---
title: "Boot sector"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Boot_sector"
wikipedia_categories: ["BIOS", "Booting", "Computer file systems"]
related: ["[[Volume boot record]]", "[[Cylinder-head-sector]]", "[[EFI system partition]]", "[[Execute in place]]", "[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]"]
---

# Boot sector

A boot sector is the sector of a persistent data storage device (e.g., hard disk, floppy disk, optical disc, etc.) which contains machine code to be loaded into random-access memory (RAM) and then executed by a computer system's built-in firmware (e.g., the BIOS).
Usually, the first sector of the hard disk is the boot sector, regardless of sector size (512 or 4096 bytes) and partitioning flavor (MBR or GPT).
The purpose of defining one particular sector as the boot sector is inter-operability between firmware and various operating systems.
The purpose of chain-loading, first firmware (e.g., the BIOS), then code in the boot sector, and then, for example, an operating system, is maximal flexibility.

## Related

- [[Volume boot record]]
- [[Cylinder-head-sector]]
- [[EFI system partition]]
- [[Execute in place]]
- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Boot_sector