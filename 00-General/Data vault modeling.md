---
title: "Data vault modeling"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_vault_modeling"
wikipedia_categories: ["Data warehousing"]
related: ["[[Aggregate (data warehouse)]]", "[[Anchor modeling]]", "[[Bill Inmon]]", "[[Bitemporal modeling]]", "[[Business analytics]]", "[[Cubes (OLAP server)]]", "[[Dashboard (computing)]]", "[[Data blending]]", "[[Data extraction]]", "[[Data loading]]"]
---

# Data vault modeling

Datavault or data vault modeling is a database modeling method that is designed to provide long-term historical storage of data coming in from multiple operational systems. It is also a method of looking at historical data that deals with issues such as auditing, tracing of data, loading speed, and resilience to change, as well as emphasizing the need to trace where all the data in the database came from. This means that every row in a data vault must be accompanied by record source and load date attributes, enabling an auditor to trace values back to the source. The concept was published in 2000 by Dan Linstedt.
Data vault modeling makes no distinction between good and bad data ("bad" meaning not conforming to business rules). This is summarized in the statement that a data vault stores "a single version of the facts" (also expressed by Dan Linstedt as "all the data, all of the time") as opposed to the practice in other data warehouse methods of storing "a single version of the truth" where data that does not conform to the definitions is removed or "cleansed". A data vault enterprise data warehouse provides both a single version of facts and a single source of truth.
The modeling method is designed to be resilient to change in the business environment where the data being stored is coming from, by explicitly separating structural information from descriptive attributes. Data vault is designed to enable parallel loading as much as possible, so that very large implementations can scale out without the need for major redesign.
Unlike the star schema (dimensional modelling) and the classical relational model (3NF), data vault and anchor modeling are well-suited for capturing changes that occur when a source system is changed or added, but are considered advanced techniques which require experienced data architects. Both data vaults and anchor models are entity-based models  but anchor models have a more normalized approach.

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

- Wikipedia: https://en.wikipedia.org/wiki/Data_vault_modeling