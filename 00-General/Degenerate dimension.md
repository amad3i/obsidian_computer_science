---
title: "Degenerate dimension"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Degenerate_dimension"
wikipedia_categories: ["Data warehousing", "Metadata"]
related: ["[[Data transformation (computing)]]", "[[Dimension (data warehouse)]]", "[[Measure (data warehouse)]]", "[[Aggregate (data warehouse)]]", "[[Analyzed Layout and Text Object]]", "[[Anchor modeling]]", "[[ANPA-1312]]", "[[Archive bit]]", "[[Asset Description Metadata Schema]]", "[[Author name disambiguation]]"]
---

# Degenerate dimension

According to Ralph Kimball, in a data warehouse, a degenerate dimension is a dimension key (primary key for a dimension table) in the fact table that does not have its own dimension table, because all the interesting attributes have been placed in analytic dimensions. The term "degenerate dimension" was originated by Ralph Kimball.

As Bob Becker says:Degenerate dimensions commonly occur when the fact table's grain is a single transaction (or transaction line). Transaction control header numbers assigned by the operational business process are typically degenerate dimensions, such as order, ticket, credit card transaction, or check numbers. These degenerate dimensions are natural keys of the "parents" of the line items.
Even though there is no corresponding dimension table of attributes, degenerate dimensions can be quite useful for grouping together related fact tables rows. For example, retail point-of-sale transaction numbers tie all the individual items purchased together into a single market basket. In health care, degenerate dimensions can group the claims items related to a single hospital stay or episode of care.

## Related

- [[Data transformation (computing)]]
- [[Dimension (data warehouse)]]
- [[Measure (data warehouse)]]
- [[Aggregate (data warehouse)]]
- [[Analyzed Layout and Text Object]]
- [[Anchor modeling]]
- [[ANPA-1312]]
- [[Archive bit]]
- [[Asset Description Metadata Schema]]
- [[Author name disambiguation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Degenerate_dimension