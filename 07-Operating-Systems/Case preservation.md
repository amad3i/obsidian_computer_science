---
title: "Case preservation"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Case_preservation"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Case preservation

In file systems, case preservation is the preservation of the letter case (uppercase or lowercase) of letters in file names.  If an attempt is made to create a file named "ThisIsAFile" on a file system that preserves letter case, the file's name will be "ThisIsAFile", rather than, for example, "thisisafile" or "THISISAFILE".
In contrast, a file system that does not preserve letter case will typically store letters in file names either as all lowercase or as all uppercase, and the letter case information will thus be lost.  If an attempt is made to create a file named "ThisIsAFile" on a file system that does not preserve letter case, the file's name will be "thisisafile" if letters are stored as all lowercase or "THISISAFILE" if letters are stored as all uppercase.

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

- Wikipedia: https://en.wikipedia.org/wiki/Case_preservation