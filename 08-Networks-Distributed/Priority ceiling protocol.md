---
title: "Priority ceiling protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Priority_ceiling_protocol"
wikipedia_categories: ["Concurrency control", "Real-time computing"]
related: ["[[Priority inheritance]]", "[[ACID]]", "[[Advanced Synchronization Facility]]", "[[AQuoSA]]", "[[Arthur Pollen]]", "[[Barrier (computer science)]]", "[[Commitment ordering]]", "[[CompactDAQ]]", "[[CompactRIO]]", "[[Concurrency control]]"]
---

# Priority ceiling protocol

In real-time computing, the priority ceiling protocol is a synchronization protocol for shared resources to avoid unbounded priority inversion and mutual deadlock due to wrong nesting of critical sections. In this protocol each resource is assigned a priority ceiling, which is a priority equal to the highest priority of any task which may lock the resource. The protocol works by temporarily raising the priorities of tasks in certain situations, thus it requires a scheduler that supports dynamic priority scheduling.

## Related

- [[Priority inheritance]]
- [[ACID]]
- [[Advanced Synchronization Facility]]
- [[AQuoSA]]
- [[Arthur Pollen]]
- [[Barrier (computer science)]]
- [[Commitment ordering]]
- [[CompactDAQ]]
- [[CompactRIO]]
- [[Concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Priority_ceiling_protocol