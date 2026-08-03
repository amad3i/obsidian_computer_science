---
title: "Data plane"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_plane"
wikipedia_categories: ["Internet architecture", "Routers (computing)"]
related: ["[[Control plane]]", "[[Core router]]", "[[Gateway (telecommunications)]]", "[[HERMES-A-MINOTAUR]]", "[[Management plane]]", "[[Router (computing)]]", "[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]"]
---

# Data plane

In routing, the data plane, sometimes called the forwarding plane or user plane, defines the part of the router architecture that determines what to do with packets arriving on an inbound interface. Most commonly, it refers to a table in which the router looks up the destination address of the incoming packet and retrieves the information necessary to determine the path from the receiving element, through the internal forwarding fabric of the router, and to the proper outgoing interface(s).
In certain cases the table may specify that a packet is to be discarded. In such cases, the router may return an ICMP "destination unreachable" or other appropriate code. Some security policies, however, dictate that the router should drop the packet silently, in order that a potential attacker does not become aware that a target is being protected.
The incoming forwarding element will also decrement the time-to-live (TTL) field of the packet, and, if the new value is zero, discard the packet. While the Internet Protocol (IP) specification indicates that an Internet Control Message Protocol (ICMP) time exceeded message should be sent to the originator of the packet (i.e. the node indicated by the source address), the router may be configured to drop the packet silently (again according to security policies).
Depending on the specific router implementation, the table in which the destination address is looked up could be the routing table (also known as the routing information base, RIB), or a separate forwarding information base (FIB) that is populated (i.e., loaded) by the routing control plane, but used by the forwarding plane for look-ups at much higher speeds. Before or after examining the destination, other tables may be consulted to determine how to handle packets based on other characteristics, such as the source address, the IP protocol identifier field, or Transmission Control Protocol (TCP) or User Datagram Protocol (UDP) port number.
Forwarding plane functions run in the forwarding element.  High-performance routers often have multiple distributed forwarding elements, so that the router increases performance with parallel processing.
The outgoing interface will encapsulate the packet in the appropriate data link protocol.  Depending on the router software and its configuration, functions, usually implemented at the outgoing interface, may set various packet fields, such as the DSCP field used by differentiated services.
In general, the passage from the input interface directly to an output interface, through the fabric with minimum modification at the output interface, is called the fast path of the router. If the packet needs significant processing, such as segmentation or encryption, it may go onto a slower path, which is sometimes called the services plane of the router. Service planes can make forwarding or processing decisions based on higher-layer information, such as a Web URL contained in the packet payload.

## Related

- [[Control plane]]
- [[Core router]]
- [[Gateway (telecommunications)]]
- [[HERMES-A-MINOTAUR]]
- [[Management plane]]
- [[Router (computing)]]
- [[6bone]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]
- [[AiScaler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_plane