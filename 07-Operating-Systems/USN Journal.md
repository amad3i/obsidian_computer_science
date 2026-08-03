---
title: "USN Journal"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/USN_Journal"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# USN Journal

The USN Journal (Update Sequence Number Journal), or Change Journal, is a feature of the Windows NT file system (NTFS) which maintains a record of changes made to the volume. It is not to be confused with the journal used for the NTFS file system journaling.
When Windows 2000 was released, Microsoft created NTFS version 3.0, which included several new features and improvements over older versions of the file system. One of these was a new system management feature that is very useful for certain types of applications. Under Windows 2000, NTFS 3.0 partitions can be set to keep track of changes to files and directories on the volume, providing a record of when and what was done to the various objects. When enabled, the system records all changes made to the volume in the USN Journal, which is the name also used to describe the feature itself.
One journal is maintained for each NTFS volume and stored in the NTFS metafile named $Extend\$UsnJrnl. It begins as an empty file. Whenever a change is made to the volume, a record is added to the file. Each record is identified by a 64-bit Update Sequence Number or USN (for this reason Change Journals are sometimes called USN Journals). Each record in the Change Journal contains the USN, the name of the file, and information about what the change was.
The Change Journal describes the changes that took place using bit flags (e.g. USN_REASON_DATA_OVERWRITE), therefore it does not include all the data or details associated with the change. For this reason the Change Journal cannot be used to undo operations on files within NTFS.

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

- Wikipedia: https://en.wikipedia.org/wiki/USN_Journal