---
title: "Resource Reservation Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Resource_Reservation_Protocol"
wikipedia_categories: ["Internet architecture", "Internet protocols", "Transport layer protocols"]
related: ["[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Fast and Secure Protocol]]", "[[Identifier-Locator Network Protocol]]", "[[Multipurpose Transaction Protocol]]", "[[QUIC]]", "[[Reliable Data Protocol]]", "[[Reliable Datagram Sockets]]"]
---

# Resource Reservation Protocol

The Resource Reservation Protocol (RSVP) is a transport layer protocol designed to reserve resources across a network using the integrated services model. RSVP operates over an IPv4 or IPv6 and provides receiver-initiated setup of resource reservations for multicast or unicast data flows. It does not transport application data but is similar to a control protocol, like Internet Control Message Protocol (ICMP) or Internet Group Management Protocol (IGMP). RSVP is described in RFC 2205. It is assigned the IP protocol number 46.
RSVP can be used by hosts and routers to request or deliver specific levels of quality of service (QoS) for application data streams. RSVP defines how applications place reservations and how they can relinquish the reserved resources once no longer required. RSVP operations will generally result in resources being reserved in each node along a path. RSVP is not a routing protocol but was designed to interoperate with current and future routing protocols.
In 2003, development effort was shifted from RSVP to RSVP-TE for teletraffic engineering. Next Steps in Signaling (NSIS) was a proposed replacement for RSVP.

## Related

- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Fast and Secure Protocol]]
- [[Identifier-Locator Network Protocol]]
- [[Multipurpose Transaction Protocol]]
- [[QUIC]]
- [[Reliable Data Protocol]]
- [[Reliable Datagram Sockets]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Resource_Reservation_Protocol