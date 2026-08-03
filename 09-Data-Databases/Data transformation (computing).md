---
title: "Data transformation (computing)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_transformation_(computing)"
wikipedia_categories: ["Data management", "Data warehousing", "Metadata"]
related: ["[[Asset Description Metadata Schema]]", "[[Author name disambiguation]]", "[[Dashboard (computing)]]", "[[Data blending]]", "[[Data custodian]]", "[[Data dictionary]]", "[[Data steward]]", "[[Data warehouse automation]]", "[[Degenerate dimension]]", "[[Dimension (data warehouse)]]"]
---

# Data transformation (computing)

In computing, data transformation is the process of converting data from one format or structure into another format or structure. It is a fundamental aspect of most data integration and data management tasks such as data wrangling, data warehousing, data integration and application integration.
Data transformation can be simple or complex based on the required changes to the data between the source (initial) data and the target (final) data. Data transformation is typically performed via a mixture of manual and automated steps. Tools and technologies used for data transformation can vary widely based on the format, structure, complexity, and volume of the data being transformed.
A master data recast is another form of data transformation where the entire database of data values is transformed or recast without extracting the data from the database.  All data in a well-designed database is directly or indirectly related to a limited set of master database tables by a network of foreign key constraints.  Each foreign key constraint is dependent upon a unique database index from the parent database table.  Therefore, when the proper master database table is recast with a different unique index, the directly and indirectly related data are also recast or restated.  The directly and indirectly related data may also still be viewed in the original form since the original unique index still exists with the master data.  Also, the database recast must be done in such a way as to not impact the applications architecture software.
When the data mapping is indirect via a mediating data model, the process is also called data mediation.

## Related

- [[Asset Description Metadata Schema]]
- [[Author name disambiguation]]
- [[Dashboard (computing)]]
- [[Data blending]]
- [[Data custodian]]
- [[Data dictionary]]
- [[Data steward]]
- [[Data warehouse automation]]
- [[Degenerate dimension]]
- [[Dimension (data warehouse)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_transformation_(computing)