---
title: "Shared-disk architecture"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Shared-disk_architecture"
wikipedia_categories: ["Data partitioning", "Distributed computing architecture", "Software architecture"]
related: ["[[Bulkhead pattern]]", "[[Connection broker]]", "[[Database-centric architecture]]", "[[GemStone-S]]", "[[Multitier architecture]]", "[[Shared-nothing architecture]]", "[[Transparency (human–computer interaction)]]", "[[4+1 architectural view model]]", "[[Active reviews for intermediate designs]]", "[[Aerospike (database)]]"]
---

# Shared-disk architecture

A shared-disk architecture (SD) is a distributed computing architecture in which the nodes share same disk devices but each node has its own private memory. The disks have active nodes which all share memory in case of any failures. In this architecture, the disks are accessible from all the cluster nodes. This architecture has quick adaptability to the changing workloads. It uses robust optimization techniques. Multiple processors can access all disks directly via intercommunication network and every processor has local memory.
It contrasts with shared-nothing architecture, in which all nodes have sole access to distinct disks, and with shared-memory, in which they also share memory.
Shared-disk has two advantages over Shared-memory. Firstly, each processor has its own memory, the memory bus is not a bottleneck; secondly, the system offers a simple way to provide a degree of fault tolerance.

## Related

- [[Bulkhead pattern]]
- [[Connection broker]]
- [[Database-centric architecture]]
- [[GemStone-S]]
- [[Multitier architecture]]
- [[Shared-nothing architecture]]
- [[Transparency (human–computer interaction)]]
- [[4+1 architectural view model]]
- [[Active reviews for intermediate designs]]
- [[Aerospike (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shared-disk_architecture