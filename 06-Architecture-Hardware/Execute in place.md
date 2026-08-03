---
title: "Execute in place"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Execute_in_place"
wikipedia_categories: ["Booting", "Computer file systems", "Firmware"]
related: ["[[Board support package]]", "[[Boot sector]]", "[[EFI system partition]]", "[[Hardware abstraction]]", "[[Volume boot record]]", "[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]"]
---

# Execute in place

In computer science, execute in place (XIP) is a method of executing programs directly from long-term storage rather than copying it into RAM. It is an extension of using shared memory to reduce the total amount of memory required.
Its general effect is that the program text consumes no writable memory, saving it for dynamic data, and that all instances of the program are run from a single copy.
For this to work, several criteria have to be met:

The storage must provide a similar interface to the CPU as regular memory (or an adaptive layer must be present).
This interface must provide sufficiently fast read operations with a random access pattern.
The file system, if one is used, needs to expose appropriate mapping functions.
The program must either be linked to be aware of the address the storage appears at in the system or be position-independent.
The program must not modify data within the loaded image.
The storage requirements are usually met by using NOR flash memory or EEPROM, which can be byte-addressed for read operations, although it is a bit slower than normal system RAM in most setups.

## Related

- [[Board support package]]
- [[Boot sector]]
- [[EFI system partition]]
- [[Hardware abstraction]]
- [[Volume boot record]]
- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Execute_in_place