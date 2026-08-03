---
title: "Record-oriented file system"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Record-oriented_file_system"
wikipedia_categories: ["Computer file systems"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Record-oriented file system

In computer science, a record-oriented file system is a file system where data are stored as collections of records. This is in contrast to a stream file system, where the data are treated as an unformatted stream of bytes.
Record-oriented file systems are abstractions of files kept on paper in earlier times. A record might contain data associated with a particular, e.g., building, contact, employee, part, venue.
There are several different possible record formats; the details vary depending on the particular system. In general the formats can be fixed-length or variable length, with different physical organizations or padding mechanisms; metadata may be associated with the file records to define the record length, or the data may be part of the record. Different access methods for records may be provided, for example records may be retrieved in sequential order, by key, or by record number.

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

- Wikipedia: https://en.wikipedia.org/wiki/Record-oriented_file_system