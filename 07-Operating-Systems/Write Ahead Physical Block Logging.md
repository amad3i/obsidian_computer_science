---
title: "Write Ahead Physical Block Logging"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Write_Ahead_Physical_Block_Logging"
wikipedia_categories: ["Computer file systems", "Computer storage stubs", "Disk file systems", "NetBSD", "Unix file system technology"]
related: ["[[Soft updates]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Block allocation map]]", "[[Dancing tree]]", "[[Design of the FAT file system]]", "[[Fast Virtual Disk]]", "[[File Allocation Table]]", "[[HFS Plus]]", "[[Hierarchical File System (Apple)]]"]
---

# Write Ahead Physical Block Logging

Write Ahead Physical Block Logging (WAPBL) provides meta data journaling for file systems in conjunction with Fast File System (FFS) to accomplish rapid filesystem consistency after an unclean shutdown of the filesystem and better general use performance over regular FFS.  With the journal, fsck is no longer required at system boot; instead, the system can replay the journal in order to correct any inconsistencies in the filesystem if the system has been shut down in an unclean fashion.

## Related

- [[Soft updates]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Block allocation map]]
- [[Dancing tree]]
- [[Design of the FAT file system]]
- [[Fast Virtual Disk]]
- [[File Allocation Table]]
- [[HFS Plus]]
- [[Hierarchical File System (Apple)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Write_Ahead_Physical_Block_Logging