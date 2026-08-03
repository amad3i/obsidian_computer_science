---
title: "Journaling file system"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Journaling_file_system"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Journaling file system

A journaling file system is a file system that keeps track of changes not yet committed to the file system's main part by recording the goal of such changes in a data structure known as a "journal", which is usually a circular log.  In the event of a system crash or power failure, such file systems can be brought back online more quickly with a lower likelihood of becoming corrupted.
Depending on the actual implementation, a journaling file system may only keep track of stored metadata, resulting in improved performance at the expense of increased possibility for data corruption.  Alternatively, a journaling file system may track both stored data and related metadata, while some implementations allow selectable behavior in this regard.

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

- Wikipedia: https://en.wikipedia.org/wiki/Journaling_file_system