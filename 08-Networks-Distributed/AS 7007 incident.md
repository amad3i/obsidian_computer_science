---
title: "AS 7007 incident"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/AS_7007_incident"
wikipedia_categories: ["1990s internet outages", "April 1997", "Internet architecture", "Routing"]
related: ["[[AiScaler]]", "[[Any-source multicast]]", "[[Classless Inter-Domain Routing]]", "[[Default route]]", "[[Echo (communications protocol)]]", "[[Hot-potato routing]]", "[[IEEE 802.1aq]]", "[[Internet Protocol Options]]", "[[Internet Routing Registry]]", "[[Multihoming]]"]
---

# AS 7007 incident

The AS 7007 incident was a major disruption of the Internet on April 25, 1997, that started with a router operated by autonomous system 7007 (MAI Network Services, although sometimes incorrectly attributed to the Florida Internet Exchange) accidentally leaking a substantial part of its entire routing table to the Internet, creating a routing black hole.
Probably because of a bug in the affected router, the routes leaked were deaggregated to /24 prefixes, which were more specific than the routes originally present on the Internet, and had the AS path rewritten to 7007, leading the Border Gateway Protocol (BGP) used by the Internet's routers to prefer the leaked routes. This was then exacerbated by other problems that prevented the routes from disappearing from other networks' routing tables, even after the original router that had sent them had been disconnected. The combination of these factors resulted in an extended disruption of operations throughout the Internet.
Analysis of this event led to major changes in Internet Service Providers' BGP operations intended to mitigate the effects of any subsequent similar events.

## Related

- [[AiScaler]]
- [[Any-source multicast]]
- [[Classless Inter-Domain Routing]]
- [[Default route]]
- [[Echo (communications protocol)]]
- [[Hot-potato routing]]
- [[IEEE 802.1aq]]
- [[Internet Protocol Options]]
- [[Internet Routing Registry]]
- [[Multihoming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/AS_7007_incident