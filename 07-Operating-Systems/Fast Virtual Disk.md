---
title: "Fast Virtual Disk"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast_Virtual_Disk"
wikipedia_categories: ["Computer file systems", "Disk file systems", "Free special-purpose file systems", "Storage virtualization", "Virtualization software for Linux"]
related: ["[[Apple File System]]", "[[Design of the FAT file system]]", "[[File Allocation Table]]", "[[File virtualization]]", "[[HFS Plus]]", "[[Hierarchical File System (Apple)]]", "[[High Performance File System]]", "[[Lustre (file system)]]", "[[Nasan]]", "[[Next3]]"]
---

# Fast Virtual Disk

Fast Virtual Disk (better known as FVD) is a virtualization-oriented disk image file format developed by IBM for the QEMU virtualization platform. It differs from existing paravirtualization-centric virtual disk image formats through a design that emphasizes lack of contention and separation of concerns between the host and guest kernels through deduplication of filesystem and block layer storage management.
FVD can be written either directly to a physical or logical blockstore (avoiding host filesystem overheads), or to a regular host file system file. It strives to maintain similarity to raw disk layouts, eliminate host filesystem and disk image compression overheads, and minimize metadata-related overheads.

## Related

- [[Apple File System]]
- [[Design of the FAT file system]]
- [[File Allocation Table]]
- [[File virtualization]]
- [[HFS Plus]]
- [[Hierarchical File System (Apple)]]
- [[High Performance File System]]
- [[Lustre (file system)]]
- [[Nasan]]
- [[Next3]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fast_Virtual_Disk