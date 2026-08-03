---
title: "Apple Partition Map"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Apple_Partition_Map"
wikipedia_categories: ["Apple Inc. file systems", "Computer file systems", "Disk partitions", "MacOS"]
related: ["[[Apple File System]]", "[[HFS Plus]]", "[[EFI system partition]]", "[[Hierarchical File System (Apple)]]", "[[Access method]]", "[[Allocate-on-flush]]", "[[Apple Filing Protocol]]", "[[Archive bit]]", "[[Archive file]]", "[[Automator (macOS)]]"]
---

# Apple Partition Map

Apple Partition Map (APM) is a partition scheme used to define the low-level organization of data on disks formatted for use with 68k and PowerPC Macintosh computers. It was introduced with the Macintosh II.
Disks using the Apple Partition Map are divided into logical blocks, with 512 bytes usually belonging to each block. The first block, Block 0, contains an Apple-specific data structure called "Driver Descriptor Map" for the Macintosh Toolbox ROM to load driver updates and patches before loading from an MFS or HFS partition. Because APM allows 32 bits worth of logical blocks, the historical size of an APM formatted disk using small blocks is limited to 2 TiB.
The Apple Partition Map maps out all space used (including the map) and unused (free space) on disk, unlike the minimal x86 master boot record that only accounts for used non-map partitions.  This means that every block on the disk (with the exception of the first block, Block 0) belongs to a partition.
Some hybrid disks contain both an ISO 9660 primary volume descriptor and an Apple Partition Map, thus allowing the disc to work on different types of computers, including Apple systems.

## Related

- [[Apple File System]]
- [[HFS Plus]]
- [[EFI system partition]]
- [[Hierarchical File System (Apple)]]
- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple Filing Protocol]]
- [[Archive bit]]
- [[Archive file]]
- [[Automator (macOS)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Apple_Partition_Map