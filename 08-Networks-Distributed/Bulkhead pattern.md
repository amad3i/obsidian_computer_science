---
title: "Bulkhead pattern"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Bulkhead_pattern"
wikipedia_categories: ["Distributed computing architecture", "Software architecture", "Software design patterns", "Software stubs"]
related: ["[[Multitier architecture]]", "[[Connection broker]]", "[[Data, context and interaction]]", "[[Database-centric architecture]]", "[[Debugging pattern]]", "[[Dependency injection]]", "[[Distributed design patterns]]", "[[GemStone-S]]", "[[Inversion of control]]", "[[JSP model 1 architecture]]"]
---

# Bulkhead pattern

Bulkhead pattern is a design pattern used in software architecture and distributed computing for isolating parts of an application into pools or compartments so that failure of one component will not cascade to other components. The term comes from the compartmentalized hull design of ships, where watertight sections (bulkheads) limit the flooding to a single area and thus preserve the integrity of the vessel. In software systems, this pattern is often implemented by partitioning resources such as thread pools, connection pools, or service instances, so that problems such as latency, resource exhaustion or crashes in one partition don't impact the whole system.
The bulkhead pattern is a common pattern used in microservices and cloud computing environments to improve system resilience and fault tolerance. It is often combined with other resilience patterns such as circuit breakers and retries to form a complete fault handling strategy. Although effective, improper partitioning can lead to underutilization of resources or increased system complexity, necessitating careful design and monitoring.

## Related

- [[Multitier architecture]]
- [[Connection broker]]
- [[Data, context and interaction]]
- [[Database-centric architecture]]
- [[Debugging pattern]]
- [[Dependency injection]]
- [[Distributed design patterns]]
- [[GemStone-S]]
- [[Inversion of control]]
- [[JSP model 1 architecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bulkhead_pattern