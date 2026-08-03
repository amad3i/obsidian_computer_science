---
title: "End-to-end principle"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/End-to-end_principle"
wikipedia_categories: ["Internet architecture", "Net neutrality", "Network architecture", "Programming paradigms"]
related: ["[[Darknet]]", "[[EncroChat]]", "[[Fabric Connect]]", "[[Fate-sharing]]", "[[IEEE 802.1aq]]", "[[Internet bottleneck]]", "[[Middle mile]]", "[[Peering]]", "[[6bone]]", "[[Adaptive quality of service multi-hop routing]]"]
---

# End-to-end principle

The end-to-end (E2E) principle is a design principle in computer networking that requires application-specific features (such as reliability and security) to be implemented in the communicating end nodes of the network, instead of in the network itself. Intermediary nodes (such as gateways and routers) that exist to establish the network may still implement these features to improve efficiency but do not guarantee end-to-end functionality.
The essence of what would later be called the end-to-end principle was contained in the work of Donald Davies on packet-switched networks in the 1960s. Louis Pouzin pioneered the use of the end-to-end strategy in the CYCLADES network in the 1970s. The principle was first articulated explicitly in 1981 by Saltzer, Reed, and Clark. The meaning of the end-to-end principle has been continuously reinterpreted ever since its initial articulation. Noteworthy formulations of the end-to-end principle can be found before the seminal 1981 Saltzer, Reed, and Clark paper.
A basic premise of the principle is that the payoffs from adding certain features required by the end application to the communication subsystem quickly diminish.  The end hosts have to implement these functions for correctness. Implementing a specific function incurs some resource penalties regardless of whether the function is used or not, and implementing a specific function in the network adds these penalties to all clients, whether they need the function or not.

## Related

- [[Darknet]]
- [[EncroChat]]
- [[Fabric Connect]]
- [[Fate-sharing]]
- [[IEEE 802.1aq]]
- [[Internet bottleneck]]
- [[Middle mile]]
- [[Peering]]
- [[6bone]]
- [[Adaptive quality of service multi-hop routing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/End-to-end_principle