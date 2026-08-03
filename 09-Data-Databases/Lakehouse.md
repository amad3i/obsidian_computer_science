---
title: "Lakehouse"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Lakehouse"
wikipedia_categories: ["Data management"]
related: ["[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]", "[[Association rule learning]]", "[[Astroinformatics]]"]
---

# Lakehouse

Data lakehouses are a hybrid approach that can ingest a variety of raw data formats like a data lake, while also providing ACID transactions and enforced data quality like a data warehouse.
The architecture was outlined in a 2020 paper by researchers at Databricks, who proposed combining the management features and transactional guarantees of a data warehouse with the low-cost storage and open file formats characteristic of a data lake. The term was subsequently adopted by other data platform vendors offering similar architectures.
Technically, a data lakehouse is typically built on open table formats such as Delta Lake, Apache Iceberg, or Apache Hudi, which are layered over open file formats such as Apache Parquet on object storage. These table formats add transactional semantics, schema enforcement, and time-travel queries to data stored in conventional cloud object stores, allowing multiple compute engines to read and write the same tables.
A common organizational pattern within lakehouse implementations is the "medallion" architecture, in which data is progressively refined through bronze (raw), silver (cleaned), and gold (aggregated) layers within the same storage system. This allows business intelligence, machine learning, and other analytic workloads to operate against a single managed copy of the data rather than separate warehouse and lake systems.

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

- Wikipedia: https://en.wikipedia.org/wiki/Lakehouse