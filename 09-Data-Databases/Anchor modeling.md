---
title: "Anchor modeling"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Anchor_modeling"
wikipedia_categories: ["Data modeling", "Data modeling diagrams", "Data warehousing", "Database normalization"]
related: ["[[Bitemporal modeling]]", "[[Armstrong's axioms]]", "[[Database normalization]]", "[[Dimensional modeling]]", "[[IDEF1X]]", "[[Log trigger]]", "[[Lossless join decomposition]]", "[[Reverse star schema]]", "[[Single source of truth]]", "[[Single version of the truth]]"]
---

# Anchor modeling

Anchor modeling is an agile database modeling technique suited for information that changes over time both in structure and content. It provides a graphical notation used for conceptual modeling similar to that of entity-relationship modeling, with extensions for working with temporal data. The modeling technique involves four modeling constructs: the anchor, attribute, tie and knot, each capturing different aspects of the domain being modeled. The resulting models can be translated to physical database designs using formalized rules. When such a translation is done the tables in the relational database will mostly be in the sixth normal form.
Unlike the star schema (dimensional modelling) and the classical relational model (3NF), data vault and anchor modeling are well-suited for capturing changes that occur when a source system is changed or added, but are considered advanced techniques which require experienced data architects. Both data vaults and anchor models are entity-based models, but anchor models have a more normalized approach.

## Related

- [[Bitemporal modeling]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Anchor_modeling