---
title: "Snowflake schema"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Snowflake_schema"
wikipedia_categories: ["Data warehousing", "Online analytical processing"]
related: ["[[OLAP cube]]", "[[Aggregate (data warehouse)]]", "[[Anchor modeling]]", "[[Bill Inmon]]", "[[Bitemporal modeling]]", "[[Business analytics]]", "[[Comparison of OLAP servers]]", "[[Cubes (OLAP server)]]", "[[Dashboard (computing)]]", "[[Data blending]]"]
---

# Snowflake schema

In computing, a snowflake schema or snowflake model is a logical arrangement of tables in a multidimensional database such that the entity relationship diagram resembles a snowflake  shape. The snowflake schema is represented by centralized fact tables which are connected to multiple dimensions. "Snowflaking" is a method of normalizing the dimension tables in a star schema. When it is completely normalized along all the dimension tables, the resultant structure resembles a snowflake with the fact table in the middle. The principle behind snowflaking is normalization of the dimension tables by removing low cardinality attributes and forming separate tables.
The snowflake schema is similar to the star schema. However, in the snowflake schema, dimensions are normalized into multiple related tables, whereas the star schema's dimensions are denormalized with each dimension represented by a single table. A complex snowflake shape emerges when the dimensions of a snowflake schema are elaborate, having multiple levels of relationships, and the child tables have multiple parent tables ("forks in the road").

## Related

- [[OLAP cube]]
- [[Aggregate (data warehouse)]]
- [[Anchor modeling]]
- [[Bill Inmon]]
- [[Bitemporal modeling]]
- [[Business analytics]]
- [[Comparison of OLAP servers]]
- [[Cubes (OLAP server)]]
- [[Dashboard (computing)]]
- [[Data blending]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Snowflake_schema