---
title: "MAC times"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/MAC_times"
wikipedia_categories: ["Computer file systems", "Computer forensics"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# MAC times

MAC times are pieces of file system metadata which record when certain events pertaining to a computer file occurred most recently. The events are usually described as "modification" (the data in the file was modified), "access" (some part of the file was read), and "metadata change" (the file's permissions or ownership were modified), although the acronym is derived from the "mtime", "atime", and "ctime" structures maintained by Unix file systems. Windows file systems do not update ctime when a file's metadata is changed, instead using the field to record the time when a file was first created, known as "creation time" or "birth time". Some other systems also record birth times for files, but there is no standard name for this metadata; ZFS, for example, stores birth time in a field called "crtime". MAC times are commonly used in computer forensics. The name Mactime was originally coined by Dan Farmer, who wrote a tool with the same name.

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

- Wikipedia: https://en.wikipedia.org/wiki/MAC_times