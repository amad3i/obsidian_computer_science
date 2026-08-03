---
title: "Basic partitioned access method"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Basic_partitioned_access_method"
wikipedia_categories: ["Computer file systems", "IBM mainframe operating systems"]
related: ["[[Access method]]", "[[Data set (IBM mainframe)]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Basic partitioned access method

In IBM mainframe operating systems, basic partitioned access method (BPAM) is an access method  for libraries, called partitioned datasets (PDSes) in IBM terminology. BPAM is used in OS/360, OS/VS2, MVS, z/OS, and others.
A PDS consists of members (internally identical to sequential data sets), registered in a list called the directory. The combination of members and directory is a single dataset on disk. The directory contains a list of member's names (8 characters, padded on the right with blanks, as required) and member's addresses. Addresses are relative to the start of the dataset in order to allow the PDS to be moved to a different disk location.
Partitioned datasets can store any type of data, but they are often used to store executable programs, or load modules, sometimes called binaries in other systems. Other uses include system assembler macro definitions, job control procedures, and program source code.

## Related

- [[Access method]]
- [[Data set (IBM mainframe)]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Block allocation map]]
- [[Block availability map]]
- [[Block suballocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Basic_partitioned_access_method