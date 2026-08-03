---
title: "Physicalization"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Physicalization"
wikipedia_categories: ["Cloud computing", "Computer hardware stubs"]
related: ["[[Abiquo Enterprise Edition]]", "[[AI data center]]", "[[AI infrastructure]]", "[[Alibaba Cloud]]", "[[Amaryllo]]", "[[Amazon Elastic Compute Cloud]]", "[[Amazon Kinesis]]", "[[Ampere Computing]]", "[[Apache CarbonData]]", "[[Apache Drill]]"]
---

# Physicalization

Physicalization of computer hardware is a way to place multiple physical machines in a rack unit. It is the opposite of virtualization. It can be a way to reduce hardware costs, since in some cases, server processors cost more per core than energy efficient laptop processors, which may make up for added cost of board level integration.  While Moore's law makes increasing integration less expensive, some jobs require much I/O bandwidth, which may be less expensive to provide using many less-integrated processors.
Applications and services that are I/O bound are likely to benefit from such physicalized environments.  This ensures that each operating system instance is running on a processor that has its own network interface card, host bus and I/O sub-system unlike in the case of a multi-core servers where a single I/O sub-system is shared between all the cores / VMs.

## Related

- [[Abiquo Enterprise Edition]]
- [[AI data center]]
- [[AI infrastructure]]
- [[Alibaba Cloud]]
- [[Amaryllo]]
- [[Amazon Elastic Compute Cloud]]
- [[Amazon Kinesis]]
- [[Ampere Computing]]
- [[Apache CarbonData]]
- [[Apache Drill]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Physicalization