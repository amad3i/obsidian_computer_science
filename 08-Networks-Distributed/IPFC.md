---
title: "IPFC"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IPFC"
wikipedia_categories: ["Fibre Channel", "Internet protocols", "Internet stubs"]
related: ["[[Asynchronous Layered Coding]]", "[[Border Gateway Multicast Protocol]]", "[[Endpoint Handlespace Redundancy Protocol]]", "[[Extensible Name Service]]", "[[High Frequency Internet Protocol]]", "[[Internet Fibre Channel Protocol]]", "[[Internet Imaging Protocol]]", "[[Internet Open Trading Protocol]]", "[[IPv9 (China)]]", "[[Network Data Representation]]"]
---

# IPFC

IPFC stands for Internet Protocol over Fibre Channel. It governs a set of standards created in January 2006 for address resolution (ARP) and transmitting IPv4 and IPv6 network packets over a Fibre Channel (FC) network. IPFC makes up part of the FC-4 protocol-mapping layer of a Fibre Channel system.
In IPFC, each IP datagram packet is wrapped into a FC frame, with its own header, and transmitted as a sequence of one or more frames. The receiver at the other end receives the frames, strips the FC headers and reassembles the IP packet. IP datagrams of up to 65,280 bytes in size may be accommodated. ARP packet transmission works in the same fashion. Each IP datagram exchange is unidirectional, although IP and TCP allow for bidirectional communication within their protocols.
IPFC is an application protocol that is typically implemented as a device driver in an operating system. IP over FC plays a less important role in storage area networking than SCSI over Fibre Channel or IP over Ethernet. IPFC has been used, for example, to provide clock synchronization via the Network Time Protocol (NTP).

## Related

- [[Asynchronous Layered Coding]]
- [[Border Gateway Multicast Protocol]]
- [[Endpoint Handlespace Redundancy Protocol]]
- [[Extensible Name Service]]
- [[High Frequency Internet Protocol]]
- [[Internet Fibre Channel Protocol]]
- [[Internet Imaging Protocol]]
- [[Internet Open Trading Protocol]]
- [[IPv9 (China)]]
- [[Network Data Representation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IPFC