---
title: "ALTQ"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/ALTQ"
wikipedia_categories: ["BSD software", "DragonFly BSD", "FreeBSD", "Free software programmed in C", "I/O scheduling", "NetBSD", "Network performance", "Network scheduling algorithms"]
related: ["[[Busdma]]", "[[Kqueue]]", "[[FreeBSD jail]]", "[[Pfsync]]", "[[Soft updates]]", "[[Sysctl]]", "[[Vinum volume manager]]", "[[Vkernel]]", "[[Adaptive quality of service multi-hop routing]]", "[[AiScaler]]"]
---

# ALTQ

ALTQ (ALTernate Queueing) is the network scheduler for Berkeley Software Distribution.  ALTQ provides queueing disciplines, and other components related to quality of service (QoS), required to realize resource sharing. It is most commonly implemented on BSD-based routers. ALTQ is included in the base distribution of FreeBSD, NetBSD, and DragonFly BSD, and was integrated into the pf packet filter of OpenBSD but later replaced by a new queueing subsystem (it was deprecated with OpenBSD 5.5 release, and completely removed with 5.6 in 2014).
With ALTQ, packets can be assigned to queues for the purpose of bandwidth control. The scheduler defines the algorithm used to decide which packets get delayed, dropped or sent out immediately. There are five schedulers currently supported in the FreeBSD implementation of ALTQ:

cbq — Class-based Queueing. Queues attached to an interface build a tree, thus each queue can have further child queues. Each queue can have a priority and a bandwidth assigned. Priority mainly controls the time packets take to get sent out, while bandwidth has primarily effects on throughput.
CoDel — Controlled Delay. Attempts to combat bufferbloat.
fairq — Fair Queuing. Attempts to fairly distribute bandwidth among all connections.
hfsc — Hierarchical Fair Service Curve. Queues attached to an interface build a tree, thus each queue can have further child queues. Each queue can have a priority and a bandwidth assigned.  Priority mainly controls the time packets take to get sent out, while bandwidth has primarily effects on throughput.
PRIQ — Priority Queueing. Queues are flat attached to the interface, thus, queues cannot have further child queues. Each queue has a unique priority assigned, ranging from 0 to 15. Packets in the queue with the highest priority are processed first.

## Related

- [[Busdma]]
- [[Kqueue]]
- [[FreeBSD jail]]
- [[Pfsync]]
- [[Soft updates]]
- [[Sysctl]]
- [[Vinum volume manager]]
- [[Vkernel]]
- [[Adaptive quality of service multi-hop routing]]
- [[AiScaler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ALTQ