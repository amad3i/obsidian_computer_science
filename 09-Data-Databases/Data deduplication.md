---
title: "Data deduplication"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_deduplication"
wikipedia_categories: ["Data compression", "Data management"]
related: ["[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]", "[[Association rule learning]]", "[[Astroinformatics]]"]
---

# Data deduplication

In computing, data deduplication is a technique for eliminating duplicate copies of repeating data. Successful implementation of the technique can improve storage utilization, which may in turn lower capital expenditure by reducing the overall amount of storage media required to meet storage capacity needs. It can also be applied to network data transfers to reduce the number of bytes that must be sent.
The deduplication process requires comparison of data 'chunks' (also known as 'byte patterns') which are unique, contiguous blocks of data. These chunks are identified and stored during a process of analysis, and compared to other chunks within existing data. Whenever a match occurs, the redundant chunk is replaced with a small reference that points to the stored chunk. Given that the same byte pattern may occur dozens, hundreds, or even thousands of times (the match frequency is dependent on the chunk size), the amount of data that must be stored or transferred can be greatly reduced.
A related technique is single-instance (data) storage, which replaces multiple copies of content at the whole-file level with a single shared copy. While possible to combine this with other forms of data compression and deduplication, it is distinct from newer approaches to data deduplication (which can operate at the segment or sub-block level).
Deduplication is different from data compression algorithms, such as LZ77 and LZ78. Whereas compression algorithms identify redundant data inside individual files and encodes this redundant data more efficiently, the intent of deduplication is to inspect large volumes of data and identify large sections – such as entire files or large sections of files – that are identical, and replace them with a shared copy.

## Related

- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Approximate inference]]
- [[Archive site]]
- [[Asset Description Metadata Schema]]
- [[Association rule learning]]
- [[Astroinformatics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_deduplication