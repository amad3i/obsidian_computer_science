---
title: "Gutmann method"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Gutmann_method"
wikipedia_categories: ["Algorithms", "Data erasure"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# Gutmann method

The Gutmann method is an algorithm for securely erasing the contents of computer hard disk drives, such as files. Devised by Peter Gutmann and Colin Plumb and presented in the paper Secure Deletion of Data from Magnetic and Solid-State Memory in July 1996, it involved writing a series of 35 patterns over the region to be erased.
The selection of patterns assumes that the user does not know the encoding mechanism used by the drive, so it includes patterns designed specifically for three types of drives. A user who knows which type of encoding the drive uses can choose only those patterns intended for their drive. A drive with a different encoding mechanism would need different patterns.
Most of the patterns in the Gutmann method were designed for older MFM/RLL-encoded disks. Gutmann himself has noted that more modern drives no longer use these older encoding techniques, making parts of the method irrelevant. He said "In the time since this paper was published, some people have treated the 35-pass overwrite technique described in it more as a kind of voodoo incantation to banish evil spirits than the result of a technical analysis of drive encoding techniques".
Since about 2001, some ATA IDE and SATA hard drive manufacturer designs include support for the ATA Secure Erase standard, obviating the need to apply the Gutmann method when erasing an entire drive. The Gutmann method does not apply to USB sticks: a 2011 study reports that 71.7% of data remained available. On solid state drives it resulted in 0.8–4.3% recovery.

## Related

- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]
- [[Algorithmic mechanism design]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gutmann_method