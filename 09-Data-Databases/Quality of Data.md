---
title: "Quality of Data"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Quality_of_Data"
wikipedia_categories: ["Data management"]
related: ["[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]", "[[Association rule learning]]", "[[Astroinformatics]]"]
---

# Quality of Data

Quality of Data (QoD) is a designation coined by L. Veiga, that specifies and describes the required Quality of Service of a distributed storage system from the Consistency point of view of its data. It can be used to support big data management frameworks, Workflow management, and HPC systems (mainly for data replication and consistency). It takes into account data semantics, namely the Time interval of data freshness, the Sequence of tolerable number of outstanding versions of the data read before ore refresh, and the Value divergence allowed before displaying it. Initially it was based on a model from an existing research work regarding vector-field Consistency, awarded the best-paper prize in the ACM/IFIP/Usenix Middleware Conference 2007 and later enhanced for increased scalability and fault-tolerance.
This consistency model has been successfully applied and proven in big data key/value store Apache HBase, initially designed as a middleware module seating between clusters from separate data centres. The HBase-QoD coupling  minimises bandwidth usage and optimises resources allocation during replication achieving the desired consistency level at a more fine-grained level.
QoD is defined by the three-dimensions of vector k=(θ,σ,ν), but with a broader view of the issue, applicable also to large-scale data management techniques in regards to their timely delivery.

## Related

- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Approximate inference]]
- [[Archive site]]
- [[Asset Description Metadata Schema]]
- [[Association rule learning]]
- [[Astroinformatics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quality_of_Data