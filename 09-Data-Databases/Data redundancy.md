---
title: "Data redundancy"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_redundancy"
wikipedia_categories: ["Computer memory", "Data", "Data modeling", "Databases", "Fault-tolerant computer systems"]
related: ["[[Common data model]]", "[[Elasticity (data store)]]", "[[Foreign key]]", "[[Log shipping]]", "[[Lossless join decomposition]]", "[[Materialized view]]", "[[Metadata repository]]", "[[Relvar]]", "[[Synonym (database)]]", "[[2025–present global memory supply shortage]]"]
---

# Data redundancy

In computer main memory, auxiliary storage and computer buses, data redundancy is the existence of data that is additional to the actual data and permits correction of errors in stored or transmitted data. The additional data can simply be a complete copy of the actual data (a type of repetition code), or only select pieces of data that allow detection of errors and reconstruction of lost or damaged data up to a certain level.
For example, by including computed check bits, ECC memory is capable of detecting and correcting single-bit errors within each memory word, while RAID 1 combines two hard disk drives (HDDs) into a logical storage unit that allows stored data to survive a complete failure of one drive.  Data redundancy can also be used as a measure against silent data corruption; for example, file systems such as Btrfs and ZFS use data and metadata checksumming in combination with copies of stored data to detect silent data corruption and repair its effects.

## Related

- [[Common data model]]
- [[Elasticity (data store)]]
- [[Foreign key]]
- [[Log shipping]]
- [[Lossless join decomposition]]
- [[Materialized view]]
- [[Metadata repository]]
- [[Relvar]]
- [[Synonym (database)]]
- [[2025–present global memory supply shortage]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_redundancy