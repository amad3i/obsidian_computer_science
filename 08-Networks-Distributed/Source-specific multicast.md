---
title: "Source-specific multicast"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Source-specific_multicast"
wikipedia_categories: ["Internet Protocol", "Internet broadcasting", "Network protocols"]
related: ["[[Any-source multicast]]", "[[Commercial Internet Protocol Security Option]]", "[[PFCP]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]"]
---

# Source-specific multicast

Source-specific multicast (SSM) is a method of delivering multicast packets in which the only packets that are delivered to a receiver are those originating from a specific source address requested by the receiver. By limiting based on source, SSM reduces demands on the network and improves security.
SSM requires that the receiver specify the source address and explicitly excludes the use of the (*,G) join for all multicast groups in RFC 3376. Source specification is possible only in IPv4's IGMPv3 and IPv6's MLDv2.

## Related

- [[Any-source multicast]]
- [[Commercial Internet Protocol Security Option]]
- [[PFCP]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Source-specific_multicast