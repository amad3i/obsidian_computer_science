---
title: "Mount Rainier (packet writing)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Mount_Rainier_(packet_writing)"
wikipedia_categories: ["Computer file systems", "Optical computer storage media", "SCSI"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Mount Rainier (packet writing)

Mount Rainier (MRW) is a format for writable optical discs which provides the packet writing and defect management. Its goal is the replacement of the floppy disk. It is named after Mount Rainier, a volcano near Seattle, Washington, United States.
Mount Rainier can be used only with drives that explicitly support it (a part of SCSI/MMC and can work over ATAPI), but works with standard CD-R, CD-RW, DVD+/-R and DVD+/-RW media.
The physical format of MRW on the disk is managed by the drive's firmware, which remaps physical drive blocks into a virtual, defect-free space. Thus, the host computer does not see the physical format of the disk, only a sequence of data blocks capable of holding any filesystem.

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

- Wikipedia: https://en.wikipedia.org/wiki/Mount_Rainier_(packet_writing)