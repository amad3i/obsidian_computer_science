---
title: "Dimension (data warehouse)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Dimension_(data_warehouse)"
wikipedia_categories: ["Data warehousing", "Metadata"]
related: ["[[Data transformation (computing)]]", "[[Degenerate dimension]]", "[[Measure (data warehouse)]]", "[[Aggregate (data warehouse)]]", "[[Analyzed Layout and Text Object]]", "[[Anchor modeling]]", "[[ANPA-1312]]", "[[Archive bit]]", "[[Asset Description Metadata Schema]]", "[[Author name disambiguation]]"]
---

# Dimension (data warehouse)

A dimension is a structure that categorizes facts and measures in order to enable users to answer business questions. Commonly used dimensions are people, products, place and time. (Note: People and time sometimes are not modeled as dimensions.)
In a data warehouse, dimensions provide structured labeling information to otherwise unordered numeric measures. The dimension is a data set composed of individual, non-overlapping data elements. The primary functions of dimensions are threefold: to provide filtering, grouping and labelling.
These functions are often described as "slice and dice". A common data warehouse example involves sales as the measure, with customer and product as dimensions. In each sale a customer buys a product. The data can be sliced by removing all customers except for a group under study, and then diced by grouping by product.
A dimensional data element is similar to a categorical variable in statistics.
Typically dimensions in a data warehouse are organized internally into one or more hierarchies. "Date" is a common dimension, with several possible hierarchies:

"Days (are grouped into) Months (which are grouped into) Years",
"Days (are grouped into) Weeks (which are grouped into) Years"
"Days (are grouped into) Months (which are grouped into) Quarters (which are grouped into) Years"
etc.

## Related

- [[Data transformation (computing)]]
- [[Degenerate dimension]]
- [[Measure (data warehouse)]]
- [[Aggregate (data warehouse)]]
- [[Analyzed Layout and Text Object]]
- [[Anchor modeling]]
- [[ANPA-1312]]
- [[Archive bit]]
- [[Asset Description Metadata Schema]]
- [[Author name disambiguation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dimension_(data_warehouse)