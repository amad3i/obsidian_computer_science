---
title: "Shared-nothing architecture"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Shared-nothing_architecture"
wikipedia_categories: ["Data partitioning", "Distributed computing architecture"]
related: ["[[Shared-disk architecture]]", "[[Aerospike (database)]]", "[[Aggregate Level Simulation Protocol]]", "[[Altibase]]", "[[Amoeba (operating system)]]", "[[Andrew Project]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]", "[[Apache Samza]]", "[[Apache Storm]]"]
---

# Shared-nothing architecture

A shared-nothing architecture (SN) is a distributed computing architecture in which each update request is satisfied by a single node (processor/memory/storage unit) in a computer cluster. The intent is to eliminate contention among nodes. Nodes do not share (independently access) the same memory or storage. 
One alternative architecture is shared everything, in which requests are satisfied by arbitrary combinations of nodes. This may introduce contention, as multiple nodes may seek to update the same data at the same time. It also contrasts with shared-disk and shared-memory architectures. 
SN eliminates single points of failure, allowing the overall system to continue operating despite failures in individual nodes and allowing individual nodes to upgrade hardware or software without a system-wide shutdown.
A SN system can scale simply by adding nodes, since no central resource bottlenecks the system. In databases, a term for the part of a database on a single node is a shard. A SN system typically partitions its data among many nodes. A refinement is to replicate commonly used but infrequently modified data across many nodes, allowing more requests to be resolved on a single node.

## Related

- [[Shared-disk architecture]]
- [[Aerospike (database)]]
- [[Aggregate Level Simulation Protocol]]
- [[Altibase]]
- [[Amoeba (operating system)]]
- [[Andrew Project]]
- [[Apache Accumulo]]
- [[Apache CouchDB]]
- [[Apache Samza]]
- [[Apache Storm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shared-nothing_architecture