---
title: "Bitemporal modeling"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Bitemporal_modeling"
wikipedia_categories: ["Data modeling", "Data modeling diagrams", "Data warehousing", "Database normalization"]
related: ["[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Database normalization]]", "[[Dimensional modeling]]", "[[IDEF1X]]", "[[Log trigger]]", "[[Lossless join decomposition]]", "[[Reverse star schema]]", "[[Single source of truth]]", "[[Single version of the truth]]"]
---

# Bitemporal modeling

Bitemporal modeling is a specific case of temporal database information modeling technique designed to handle historical data along two different timelines. This makes it possible to rewind the information to "as it actually was" in combination with "as it was recorded" at some point in time. In order to be able to do so, information cannot be discarded even if it is erroneous. Within, for example, financial reporting it is often desirable to be able to recreate an old report both as it actually looked at the time of creation and as it should have looked given corrections made to the data after its creation.
Implementations of bitemporal modeling can be done using relational databases and graph databases. As such, bitemporal modeling is considered different from dimensional modeling and complementary to database normalization. The SQL:2011 standard provides language constructs for working with bitemporal data. However, as of 2011 many of the current solutions were still vendor-specific.

## Related

- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Database normalization]]
- [[Dimensional modeling]]
- [[IDEF1X]]
- [[Log trigger]]
- [[Lossless join decomposition]]
- [[Reverse star schema]]
- [[Single source of truth]]
- [[Single version of the truth]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bitemporal_modeling