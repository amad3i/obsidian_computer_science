---
title: "HFS Plus"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/HFS_Plus"
wikipedia_categories: ["Apple Inc. file systems", "Computer file systems", "Disk file systems", "MacOS", "Macintosh operating systems"]
related: ["[[Apple File System]]", "[[Hierarchical File System (Apple)]]", "[[Apple Partition Map]]", "[[Design of the FAT file system]]", "[[Fast Virtual Disk]]", "[[File Allocation Table]]", "[[High Performance File System]]", "[[Nasan]]", "[[Next3]]", "[[Soft updates]]"]
---

# HFS Plus

HFS Plus or HFS+ (also known as Mac OS Extended or HFS Extended) is a journaling file system developed by Apple Inc.  It replaced the Hierarchical File System (HFS) as the primary file system of Apple computers with the 1998 release of Mac OS 8.1.  HFS+ continued as the primary Mac OS X file system until it was itself replaced with the Apple File System (APFS), released with macOS High Sierra in 2017. HFS+ is also one of the formats supported by the iPod digital music player. In 2026, macOS Golden Gate officially deprecated encrypted HFS+ in favor of encrypted APFS.
Compared to its predecessor HFS, also called Mac OS Standard or HFS Standard, HFS Plus supports much larger files (block addresses are 32-bit length instead of 16-bit) and using Unicode (instead of Mac OS Roman or any of several other character sets) for naming items. Like HFS, HFS Plus uses B-trees to store most volume metadata, but unlike most file systems that support hard links, HFS Plus supports hard links to directories. HFS Plus permits filenames up to 255 characters in length, and n-forked files similar to NTFS, though until 2005 almost no system software took advantage of forks other than the data fork and resource fork. HFS Plus also uses a full 32-bit allocation mapping table rather than HFS's 16 bits, improving the use of space on large disks.

## Related

- [[Apple File System]]
- [[Hierarchical File System (Apple)]]
- [[Apple Partition Map]]
- [[Design of the FAT file system]]
- [[Fast Virtual Disk]]
- [[File Allocation Table]]
- [[High Performance File System]]
- [[Nasan]]
- [[Next3]]
- [[Soft updates]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HFS_Plus