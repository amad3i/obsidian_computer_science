---
title: "Staging (data)"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Staging_(data)"
wikipedia_categories: ["Data warehousing"]
related: ["[[Aggregate (data warehouse)]]", "[[Anchor modeling]]", "[[Bill Inmon]]", "[[Bitemporal modeling]]", "[[Business analytics]]", "[[Cubes (OLAP server)]]", "[[Dashboard (computing)]]", "[[Data blending]]", "[[Data extraction]]", "[[Data loading]]"]
---

# Staging (data)

A staging area, or landing zone, is an intermediate storage area used for data processing during the extract, transform and load (ETL) process. The data staging area sits between the data source(s) and the data target(s), which are often data warehouses, data marts, or other data repositories.
Data staging areas are often transient in nature, with their contents being erased prior to running an ETL process or immediately following successful completion of an ETL process. Such a staging area is sometimes called a transient staging area (TSA).
There are staging area architectures, however, which are designed to hold data for extended periods of time for archival or troubleshooting purposes. A persistent staging area (PSA) is a type of staging area in a data warehouse which tracks the whole change history of a source table or query.

## Related

- [[Aggregate (data warehouse)]]
- [[Anchor modeling]]
- [[Bill Inmon]]
- [[Bitemporal modeling]]
- [[Business analytics]]
- [[Cubes (OLAP server)]]
- [[Dashboard (computing)]]
- [[Data blending]]
- [[Data extraction]]
- [[Data loading]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Staging_(data)