---
title: "Extract, load, transform"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Extract,_load,_transform"
wikipedia_categories: ["Computing stubs", "Data warehousing"]
related: ["[[Aggregate (data warehouse)]]", "[[Anchor modeling]]", "[[Auditory display]]", "[[Automatic system recovery]]", "[[Availability zone]]", "[[Bill Inmon]]", "[[Biological computation]]", "[[Bitemporal modeling]]", "[[Business analytics]]", "[[Canned response]]"]
---

# Extract, load, transform

Extract, load, transform (ELT) is an alternative to extract, transform, load (ETL) used with data lake implementations. In contrast to ETL, in ELT models the data is not transformed on entry to the data lake, but stored in its original raw format. This enables faster loading times. However, ELT requires sufficient processing power within the data processing engine to carry out the transformation on demand, to return the results in a timely manner. Since the data is not processed on entry to the data lake, the query and schema do not need to be defined a priori (although often the schema will be available during load since many data sources are extracts from databases or similar structured data systems and hence have an associated schema). ELT is a data pipeline model.

## Related

- [[Aggregate (data warehouse)]]
- [[Anchor modeling]]
- [[Auditory display]]
- [[Automatic system recovery]]
- [[Availability zone]]
- [[Bill Inmon]]
- [[Biological computation]]
- [[Bitemporal modeling]]
- [[Business analytics]]
- [[Canned response]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Extract,_load,_transform