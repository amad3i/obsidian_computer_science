---
title: "Routing in delay-tolerant networking"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Routing_in_delay-tolerant_networking"
wikipedia_categories: ["Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# Routing in delay-tolerant networking

Routing in delay-tolerant networking concerns itself with the ability to transport, or route, data from a source to a destination, which is a fundamental ability all communication networks must have. Delay- and disruption-tolerant networks (DTNs) are characterized by their lack of connectivity, resulting in a lack of instantaneous end-to-end paths.  In these challenging environments, popular ad hoc routing protocols such as AODV and DSR fail to establish routes.  This is due to these protocols trying to first establish a complete route and then, after the route has been established, forward the actual data.  However, when instantaneous end-to-end paths are difficult or impossible to establish, routing protocols must take to a "store and forward" approach, where data is incrementally moved and stored throughout the network in hopes that it will eventually reach its destination.  A common technique used to maximize the probability of a message being successfully transferred is to replicate many copies of the message in hopes that one will succeed in reaching its destination.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Routing_in_delay-tolerant_networking