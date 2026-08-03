---
title: "Slowly changing dimension"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Slowly_changing_dimension"
wikipedia_categories: ["Data modeling", "Data warehousing"]
related: ["[[Anchor modeling]]", "[[Bitemporal modeling]]", "[[Dimensional modeling]]", "[[Log trigger]]", "[[Reverse star schema]]", "[[Star schema]]", "[[Aggregate (data warehouse)]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]", "[[Bill Inmon]]"]
---

# Slowly changing dimension

In data management and data warehousing, a slowly changing dimension (SCD) is a dimension that stores data which, while generally stable, may change over time, often in an unpredictable manner. This contrasts with a rapidly changing dimension, such as transactional parameters like customer ID, product ID, quantity, and price, which undergo frequent updates. Common examples of SCDs include geographical locations, customer details, or product attributes.
Various methodologies address the complexities of SCD management. Ralph Kimball's Data Warehouse Toolkit has popularized a categorization of techniques for handling SCD attributes as Types 1 through 6. These range from simple overwrites (Type 1), to creating new rows for each change (Type 2), adding new attributes (Type 3), maintaining separate history tables (Type 4), or employing hybrid approaches (Type 6 and 7). Type 0 is available to model an attribute as not really changing at all. Each type offers a trade-off between historical accuracy, data complexity, and system performance, catering to different analytical and reporting needs. 
The challenge with SCDs lies in preserving historical accuracy while maintaining data integrity and referential integrity. For instance, a fact table tracking sales might be linked to a dimension table containing information about salespeople and their assigned regional offices. If a salesperson is transferred to a new office, historical sales reports need to reflect their previous assignment without breaking the relationships between the fact and dimension tables. SCDs provide mechanisms to manage such changes effectively.

## Related

- [[Anchor modeling]]
- [[Bitemporal modeling]]
- [[Dimensional modeling]]
- [[Log trigger]]
- [[Reverse star schema]]
- [[Star schema]]
- [[Aggregate (data warehouse)]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]
- [[Bill Inmon]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Slowly_changing_dimension