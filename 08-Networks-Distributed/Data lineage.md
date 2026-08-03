---
title: "Data lineage"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_lineage"
wikipedia_categories: ["Big data", "Data management", "Distributed computing problems"]
related: ["[[Big memory]]", "[[Approximate inference]]", "[[Astroinformatics]]", "[[Big data]]", "[[Data exhaust]]", "[[Data philanthropy]]", "[[Data stream management system]]", "[[Data version control]]", "[[Database transaction schedule]]", "[[Datafication]]"]
---

# Data lineage

Data lineage refers to the process of tracking how data is generated, transformed, transmitted and used across systems over time. It documents data's origins, transformations and movements, providing detailed visibility into its life cycle. This process simplifies the identification of errors in data analytics workflows, by enabling users to trace issues back to their root causes.
Data lineage facilitates the ability to replay specific segments or inputs of the dataflow. This can be used in debugging or regenerating lost outputs. In database systems, this concept is closely related to data provenance, which involves maintaining records of inputs, entities, systems and processes that influence data.
Data provenance provides a historical record of data origins and transformations. It supports forensic activities such as data-dependency analysis, error/compromise detection, recovery, auditing and compliance analysis: "Lineage is a simple type of why provenance."
Data governance plays a critical role in managing metadata by establishing guidelines, strategies and policies. Enhancing data lineage with data quality measures and master data management adds business value. Although data lineage is typically represented through a graphical user interface (GUI), the methods for gathering and exposing metadata to this interface can vary. Based on the metadata collection approach, data lineage can be categorized into three types: Those involving software packages for structured data, programming languages and Big data systems.
Data lineage information includes technical metadata about data transformations. Enriched data lineage may include additional elements such as data quality test results, reference data, data models, business terminology, data stewardship information, program management details and enterprise systems associated with data points and transformations. Data lineage visualization tools often include masking features that allow users to focus on information relevant to specific use cases. To unify representations across disparate systems, metadata normalization or standardization may be required.

## Related

- [[Big memory]]
- [[Approximate inference]]
- [[Astroinformatics]]
- [[Big data]]
- [[Data exhaust]]
- [[Data philanthropy]]
- [[Data stream management system]]
- [[Data version control]]
- [[Database transaction schedule]]
- [[Datafication]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_lineage