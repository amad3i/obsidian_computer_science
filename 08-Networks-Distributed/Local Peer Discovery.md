---
title: "Local Peer Discovery"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_Peer_Discovery"
wikipedia_categories: ["BitTorrent", "Computer network stubs", "Network protocols"]
related: ["[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]", "[[Bearer-Independent Call Control]]", "[[Common Industrial Protocol]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[Content Vectoring Protocol]]", "[[ControlNet]]", "[[Digital Data Communications Message Protocol]]", "[[DREAM (protocol)]]"]
---

# Local Peer Discovery

The Local Peer Discovery protocol, specified as BEP-14, is an extension to the BitTorrent file-distribution system.  It is designed to support the discovery of local BitTorrent peers, aiming to minimize the traffic through the Internet service provider's (ISP) channel and maximize use of higher-bandwidth local area networks (LANs).
Local Peer Discovery is implemented with HTTP-like messages on User Datagram Protocol (UDP) multicast group 239.192.152.143:6771 (IPv4) or ff15::efc0:988f (IPv6) which are administratively scoped multicast addresses. It's similar to Simple Service Discovery Protocol but sends BT-SEARCH instead of M-SEARCH:  

Since implementation is simple, Local Peer Discovery is implemented in several clients (μTorrent, BitTorrent/Mainline, MonoTorrent, libtorrent and its derivatives, Transmission, aria2). An alternative multicast peer discovery protocol based on ZeroConf is published as BEP 26 Zeroconf Peer Advertising and Discovery, but is not widely adopted since it is considered too complex in comparison.

## Related

- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]
- [[Bearer-Independent Call Control]]
- [[Common Industrial Protocol]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[Content Vectoring Protocol]]
- [[ControlNet]]
- [[Digital Data Communications Message Protocol]]
- [[DREAM (protocol)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_Peer_Discovery