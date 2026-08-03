---
title: "Scalable TCP"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Scalable_TCP"
wikipedia_categories: ["Computer science stubs", "Internet protocols", "TCP congestion control", "Transport layer protocols"]
related: ["[[Fast and Secure Protocol]]", "[[L4S]]", "[[Multipurpose Transaction Protocol]]", "[[QUIC]]", "[[Reliable Data Protocol]]", "[[Reliable Datagram Sockets]]", "[[Reliable User Datagram Protocol]]", "[[Resource Reservation Protocol]]", "[[SCTP packet structure]]", "[[Tsunami UDP Protocol]]"]
---

# Scalable TCP

Type of Transmission Control Protocol which is designed to provide much higher throughput and scalability.
Standard TCP recommendations as per RFC 2581 and RFC 5681 call for congestion window to be halved for each packet lost. Effectively, this process keeps halving the throughput until packet loss stops. Once the packet loss subsides, slow start kicks in to ramp the speed back up. When the window sizes are small, say 1 Mbit/s @ 200 ms round trip time and the window is about 20 packets, this recovery time is quite fast—on the order of a few seconds. But as transfer speeds approach 1 Gbit/s, the recovery time becomes half an hour and for 10 Gbit/s it's over 4 hours.

## Related

- [[Fast and Secure Protocol]]
- [[L4S]]
- [[Multipurpose Transaction Protocol]]
- [[QUIC]]
- [[Reliable Data Protocol]]
- [[Reliable Datagram Sockets]]
- [[Reliable User Datagram Protocol]]
- [[Resource Reservation Protocol]]
- [[SCTP packet structure]]
- [[Tsunami UDP Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Scalable_TCP