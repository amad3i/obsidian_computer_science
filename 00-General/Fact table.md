---
title: "Fact table"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Fact_table"
wikipedia_categories: ["Data warehousing"]
related: ["[[Aggregate (data warehouse)]]", "[[Anchor modeling]]", "[[Bill Inmon]]", "[[Bitemporal modeling]]", "[[Business analytics]]", "[[Cubes (OLAP server)]]", "[[Dashboard (computing)]]", "[[Data blending]]", "[[Data extraction]]", "[[Data loading]]"]
---

# Fact table

In data warehousing, a fact table consists of the measurements, metrics or facts of a business process. It is located at the center of a star schema or a snowflake schema surrounded by dimension tables. Where multiple fact tables are used, these are arranged as a fact constellation schema. A fact table typically has two types of columns: those that contain facts and those that are a foreign key to dimension tables. The primary key of a fact table is usually a composite key that is made up of all of its foreign keys. Fact tables contain the content of the data warehouse and store different types of measures like additive, non-additive, and semi-additive measures.
Fact tables (usually) provide the additive values that act as independent variables by which dimensional attributes are analyzed. Fact tables are often defined by their grain. The grain of a fact table represents the most atomic level by which the facts may be defined. The grain of a sales fact table might be stated as "sales volume by day by product by store". Each record in this fact table is therefore uniquely defined by a day, product, and store. Other dimensions might be members of this fact table (such as location/region) but these add nothing to the uniqueness of the fact records. These "affiliate dimensions" allow for additional slices of the independent facts but generally provide insights at a higher level of aggregation (a region contains many stores).

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

- Wikipedia: https://en.wikipedia.org/wiki/Fact_table