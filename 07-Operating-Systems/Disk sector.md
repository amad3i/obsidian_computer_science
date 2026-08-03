---
title: "Disk sector"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Disk_sector"
wikipedia_categories: ["Computer file systems", "Units of information"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Disk sector

In computer disk storage, a sector is a subdivision of a track on a magnetic disk or optical disc. For most disks, each sector stores a fixed amount of user-accessible data, traditionally 512 bytes for hard disk drives (HDDs), and 2048 bytes for CD-ROMs, DVD-ROMs and BD-ROMs. Newer HDDs and SSDs use 4096 byte (4 KiB) sectors, which is known as the Advanced Format (AF).
The sector is the minimum storage unit of a disk drive. Most disk partitioning schemes are designed to have files occupy an integral number of sectors regardless of the file's actual size. Files that do not fill a whole sector will have the remainder of their last sector filled with zeroes. In practice, operating systems typically operate on blocks of data, which may span multiple sectors.
Geometrically, the word sector means a portion of a disk between a center, two radii and a corresponding arc (see Figure 1, item B), which is shaped like a slice of a pie. Thus, the disk sector (Figure 1, item C) refers to the intersection of a track and a geometrical sector.
In modern disk drives, each physical sector is made up of two basic parts: the sector header area (typically called "ID") and the data area. The sector header contains information used by the drive and controller; this information includes sync bytes, address identification, flaw flag, and error detection and correction information. The header may also include an alternate address to be used if the sector is a bad sector. The address identification is used to ensure that the mechanics of the drive have positioned the read/write head over the correct location. The data area contains the sync bytes, user data, and an error-correcting code (ECC) that is used to check and possibly correct errors that may have been introduced into the data.

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

- Wikipedia: https://en.wikipedia.org/wiki/Disk_sector