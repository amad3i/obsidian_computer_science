---
title: "Xpress Transport Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Xpress_Transport_Protocol"
wikipedia_categories: ["Computer network stubs", "Internet Standards", "Internet protocols", "Transport layer protocols"]
related: ["[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[Fast and Secure Protocol]]", "[[Reliable Data Protocol]]", "[[Reliable Datagram Sockets]]", "[[SCTP packet structure]]", "[[User Datagram Protocol]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]"]
---

# Xpress Transport Protocol

Xpress Transport Protocol (XTP) is a transport layer protocol for high-speed networks promoted by the XTP Forum developed to replace TCP. XTP provides protocol options for error control, flow control, and rate control. Instead of separate protocols for each type of communication, XTP controls packet exchange patterns to produce different models, e.g. reliable datagrams, transactions, unreliable streams, and reliable multicast connections.
Long latency is one of the major problems in satellite communications.  Couple this with possible environmental variables and sometimes asymmetrical bandwidth conditions, the quality of service in satellite communications is sometimes lacking.  XTP addresses these issues in a variety of ways such as a Selective Retransmission algorithm that deals with loss recovery.  This works by the receiver detecting missing data packets and transmitting a list of those missing packets to the sender, who then is able to quickly resend missing packets as needed.   As stated, XTP also provides rate control in which the maximum bandwidth can be specified as well as what size burst data can be accepted.  XTP also offers a reliable multicast protocol, and the flexibility to match any specific application needs.
XTP does not employ congestion avoidance algorithms. XTP is a real-time option at Layer 4 for the US Navy SAFENET LAN Profile.

## Related

- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[Fast and Secure Protocol]]
- [[Reliable Data Protocol]]
- [[Reliable Datagram Sockets]]
- [[SCTP packet structure]]
- [[User Datagram Protocol]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Xpress_Transport_Protocol