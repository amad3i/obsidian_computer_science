---
title: "Bitmap index"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bitmap_index"
wikipedia_categories: ["Bit data structures", "Data management", "Database index techniques"]
related: ["[[BitFunnel]]", "[[Inverted index]]", "[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]"]
---

# Bitmap index

A bitmap index is a special kind of database index that uses bitmaps.
Bitmap indexes have traditionally been considered to work well for low-cardinality columns, which have a modest number of distinct values, either absolutely, or relative to the number of records that contain the data. The extreme case of low cardinality is Boolean data (e.g., does a resident in a city have internet access?), which has two values, True and False. Bitmap indexes use bit arrays (commonly called bitmaps) and answer queries by performing bitwise logical operations on these bitmaps. Bitmap indexes have a significant space and performance advantage over other structures for query of such data. Their drawback is they are less efficient than the traditional B-tree indexes for columns whose data is frequently updated: consequently, they are more often employed in read-only systems that are specialized for fast query - e.g., data warehouses, and generally unsuitable for online transaction processing applications.
Some researchers argue that bitmap indexes are also useful for moderate or even high-cardinality data (e.g., unique-valued data) which is accessed in a read-only manner, and queries access multiple bitmap-indexed columns using the AND, OR or XOR operators extensively.
Bitmap indexes are also useful in data warehousing applications for joining a large fact table to smaller dimension tables such as those arranged in a star schema.

## Related

- [[BitFunnel]]
- [[Inverted index]]
- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Approximate inference]]
- [[Archive site]]
- [[Asset Description Metadata Schema]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bitmap_index