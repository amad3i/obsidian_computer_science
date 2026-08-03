---
title: "Extent (file systems)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Extent_(file_systems)"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Extent (file systems)

In computing, an extent is a contiguous area of storage reserved for a file in a file system, represented as a range of block numbers, or tracks on count key data devices. A file can consist of zero or more extents; one file fragment requires one extent. The direct benefit is in storing each range compactly as two numbers, instead of canonically storing every block number in the range. Also, extent allocation results in less file fragmentation.
Extent-based file systems can also eliminate most of the metadata overhead of large files that would traditionally be taken up by the block-allocation tree. But because the savings are small compared to the amount of stored data (for all file sizes in general) but make up a large portion of the metadata (for large files), the overall benefits in storage efficiency and performance are slight.
In order to resist fragmentation, several extent-based file systems do allocate-on-flush. Many modern fault-tolerant file systems also do copy-on-write, although that increases fragmentation.  As a similar design, the CP/M file system uses extents as well, but those do not correspond to the definition given above. CP/M's extents appear contiguously as a single block in the combined directory/allocation table, and they do not necessarily correspond to a contiguous data area on disk.
IBM OS/360 and successors allocate files in multiples of disk tracks or cylinders. Files could originally have up to 16 extents, but this restriction has since been lifted. The initial allocation size, and the size of additional extents to be allocated if required, are specified by the user via Job Control Language. The system attempts to allocate the initial size as a contiguous area, although this may be split if contiguous space is not available.

## Related

- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Block allocation map]]
- [[Block availability map]]
- [[Block suballocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Extent_(file_systems)