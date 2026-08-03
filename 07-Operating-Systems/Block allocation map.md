---
title: "Block allocation map"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Block_allocation_map"
wikipedia_categories: ["Computer file systems", "Computer storage stubs"]
related: ["[[Allocate-on-flush]]", "[[Dancing tree]]", "[[Write Ahead Physical Block Logging]]", "[[Access method]]", "[[Aperture (computer memory)]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]"]
---

# Block allocation map

In computer file systems, a block allocation map is a data structure used to track disk blocks that are considered "in use".  Blocks may also be referred to as allocation units or clusters.
CP/M used a block allocation map in its directory.  Each directory entry could list 8 or 16 blocks (depending on disk format) that were allocated to a file.  If a file used more blocks, additional directory entries would be needed.  Thus, a single file could have multiple directory entries.  A benefit of this method is the possibility to use sparse files by declaring a large file size but only allocating blocks that are actually used.  A detriment of this method is the disk may have free space (unallocated blocks) but data cannot be appended to a file because all directory entries are used.

## Related

- [[Allocate-on-flush]]
- [[Dancing tree]]
- [[Write Ahead Physical Block Logging]]
- [[Access method]]
- [[Aperture (computer memory)]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Block_allocation_map