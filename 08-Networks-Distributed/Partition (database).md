---
title: "Partition (database)"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Partition_(database)"
wikipedia_categories: ["Data partitioning", "Database management systems"]
related: ["[[Shard (database architecture)]]", "[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]"]
---

# Partition (database)

A partition is a division of a logical database or its constituent elements into distinct independent parts. Database partitioning refers to intentionally breaking a large database into smaller ones for scalability purposes, distinct from network partitions which are a type of network fault between nodes. In a partitioned database, each piece of data belongs to exactly one partition, effectively making each partition a small database of its own. Database partitioning is normally done for manageability, performance or availability reasons, or for load balancing. It is popular in distributed database management systems, where each partition may be spread over multiple nodes, with users at the node performing local transactions on the partition. This increases performance for sites that have regular transactions involving certain views of data, whilst maintaining availability and security.
Partitioning enables distribution of datasets across multiple disks and query loads across multiple processors. For queries that operate on a single partition, each node executes queries independently on its local partition, enabling linear scaling of query throughput with additional nodes. More complex queries can be parallelized across multiple nodes, though this presents additional challenges.

## Related

- [[Shard (database architecture)]]
- [[ACID]]
- [[ANSI-SPARC Architecture]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[AutoNumber]]
- [[Azure Data Explorer]]
- [[Bidirectionalization]]
- [[Bigtable]]
- [[Block contention]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Partition_(database)