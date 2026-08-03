---
title: "Block availability map"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Block_availability_map"
wikipedia_categories: ["Computer file systems", "Data structures"]
related: ["[[Access method]]", "[[Active data structure]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block suballocation]]"]
---

# Block availability map

In computer file systems, a block availability map (BAM)   is a data structure used to track disk blocks that are considered free (available for new data). It is used along with a directory to manage files on a disk (originally only a floppy disk, and later also a hard disk).
In terms of Commodore DOS (CBM DOS) compatible disk drives, the BAM was a data structure stored in a reserved area of the disk (its size and location varied based on the physical characteristics of the disk).  For each track, the BAM consisted of a bitmap of available blocks and (usually) a count of the available blocks.  The count was held in a single byte, as all formats had 256 or fewer blocks per track. The count byte was simply the sum of all 1-bits in the bitmap of bytes for the current track.
The following table illustrates the layout of Commodore 1541 BAM.  The table would be larger for higher-capacity disks (described below).

The bitmap was contained in 3 bytes for Commodore 1541 format (single-sided) disks because it had 17 to 20 sectors per track (note 3 bytes can hold at least 20 bits).  Similarly, the Commodore 1571 used 3 bytes for the bitmap of each track, but the BAM was twice the size because there were twice as many tracks when formatted as double-sided.  In contrast, the Commodore 1581 disk drive used 5 bytes for the bitmap because the disk format had 40 blocks per track (note 5 bytes can hold 40 bits).
In the bitmap of any format, a 1 bit indicated the block was available (free), while a 0 bit indicated the block was not available (used), and the bitmap data was stored low-byte first.  So the first byte held a map for blocks 0 to 7, the second byte held a map for blocks 8 to 15, and so on.  Within a byte, the bitmap was ordered low-bit first.  For example, the first byte would represent block 0 with the least significant bit and block 7 with the most significant bit.
Storage devices by Creative Micro Designs, intended for use with CBM computers, also used a Block Availability Map which served the same purpose.  However, these devices (FD-2000, FD-4000, and CMD-HD) did not include a count byte, and the bits in each byte were reversed (high-bit first).  Although the bits were reversed (compared to CBM formats), the bytes were still stored in the same order (low-byte first).

## Related

- [[Access method]]
- [[Active data structure]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Block allocation map]]
- [[Block suballocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Block_availability_map