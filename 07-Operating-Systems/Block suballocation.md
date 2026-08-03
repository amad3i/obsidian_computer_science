---
title: "Block suballocation"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Block_suballocation"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Boot sector]]"]
---

# Block suballocation

Block suballocation is a feature of some computer file systems which allows large blocks or allocation units to be used while making efficient use of empty space at the end of large files, space which would otherwise be lost for other use to internal fragmentation.
In file systems that don't support fragments, this feature is also called tail merging or tail packing because it is commonly done by packing the "tail", or last partial block, of multiple files into a single block.

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
- [[Boot sector]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Block_suballocation