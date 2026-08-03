---
title: "Cylinder-head-sector"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Cylinder-head-sector"
wikipedia_categories: ["AT Attachment", "BIOS", "Computer file systems", "Computer storage devices", "Hard disk computer storage", "IBM storage devices", "Rotating disc computer storage media"]
related: ["[[Boot sector]]", "[[Disc spanning]]", "[[Volume boot record]]", "[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[ATA over Ethernet]]"]
---

# Cylinder-head-sector

Cylinder-head-sector (CHS) is an early method for giving addresses to each physical block of data on a hard disk drive.
It is a 3D-coordinate system made out of a vertical coordinate head, a horizontal (or radial) coordinate cylinder, and an angular coordinate sector. Head selects a circular surface: a platter in the disk (and one of its two sides). Cylinder is a cylindrical intersection through the stack of platters in a disk, centered around the disk's spindle. Combined, cylinder and head intersect to a circular line, or more precisely: a circular strip of physical data blocks called track. Sector finally selects which data block in this track is to be addressed, as the track is subdivided into several equally-sized portions, each of which is an arc of (360/n) degrees, where n is the number of sectors in the track.
CHS addresses were exposed, instead of simple linear addresses (going from 0 to the total block count on disk - 1), because early hard drives didn't come with an embedded disk controller, that would hide the physical layout. A separate generic controller card was used, so that the operating system had to know the exact physical "geometry" of the specific drive attached to the controller, to correctly address data blocks. The traditional limits were 512 bytes/sector × 63 sectors/track × 255 heads (tracks/cylinder) × 1024 cylinders, resulting in a limit of 8032.5 MiB for the total capacity of a disk.
As the geometry became more complicated (for example, with the introduction of zone bit recording) and drive sizes grew over time, the CHS addressing method became restrictive. Since the late 1980s, hard drives began shipping with an embedded disk controller that had good knowledge of the physical geometry; they would however report a false geometry to the computer, e.g., a larger number of heads than actually present, to gain more addressable space. These logical CHS values would be translated by the controller, thus CHS addressing no longer corresponded to any physical attributes of the drive.
By the mid-1990s, hard drive interfaces replaced the CHS scheme with logical block addressing (LBA), but many tools for manipulating the master boot record (MBR) partition table still aligned partitions to cylinder boundaries; thus, artifacts of CHS addressing were still seen in partitioning software by the late 2000s.
In the early 2010s, the disk size limitations imposed by MBR became problematic and the GUID Partition Table (GPT) was designed as a replacement. GPT does not use CHS anymore except in Protective MBR.

## Related

- [[Boot sector]]
- [[Disc spanning]]
- [[Volume boot record]]
- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[ATA over Ethernet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cylinder-head-sector