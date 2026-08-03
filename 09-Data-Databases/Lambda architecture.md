---
title: "Lambda architecture"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Lambda_architecture"
wikipedia_categories: ["Big data", "Data engineering", "Data processing", "Free software projects", "Software architecture"]
related: ["[[Data management platform]]", "[[Data stream management system]]", "[[List of data science software]]", "[[4+1 architectural view model]]", "[[5D optical data storage]]", "[[Active reviews for intermediate designs]]", "[[Administrative data]]", "[[Agent architecture]]", "[[Amazon Kinesis]]", "[[Analytics]]"]
---

# Lambda architecture

Lambda architecture is a data-processing architecture designed to handle massive quantities of data by taking advantage of both batch and stream-processing methods. This approach to architecture attempts to balance latency, throughput, and fault-tolerance by using batch processing to provide comprehensive and accurate views of batch data, while simultaneously using real-time stream processing to provide views of online data. The two view outputs may be joined before presentation. The rise of lambda architecture is correlated with the growth of big data, real-time analytics, and the drive to mitigate the latencies of map-reduce.
Lambda architecture depends on a data model with an append-only, immutable data source that serves as a system of record. It is intended for ingesting and processing timestamped events that are appended to existing events rather than overwriting them. State is determined from the natural time-based ordering of the data.

## Related

- [[Data management platform]]
- [[Data stream management system]]
- [[List of data science software]]
- [[4+1 architectural view model]]
- [[5D optical data storage]]
- [[Active reviews for intermediate designs]]
- [[Administrative data]]
- [[Agent architecture]]
- [[Amazon Kinesis]]
- [[Analytics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lambda_architecture