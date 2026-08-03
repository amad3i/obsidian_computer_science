---
title: "Fork (file system)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Fork_(file_system)"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Fork (file system)

In a computer file system, a fork is a set of data associated with a file-system object. File systems without forks only allow a single set of data for the contents, while file systems with forks allow multiple such contents. Every non-empty file must have at least one fork, often of default type, and depending on the file system, a file may have one or more other associated forks, which in turn may contain primary data integral to the file, or just metadata. 
Unlike extended attributes, a similar file system feature which is typically of fixed size, forks can be of variable size, possibly even larger than the file's primary data fork. The size of a file is the sum of the sizes of each fork.
Popular file systems that can use forks include Apple's HFS+ and Microsoft's NTFS.

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

- Wikipedia: https://en.wikipedia.org/wiki/Fork_(file_system)