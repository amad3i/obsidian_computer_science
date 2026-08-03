---
title: "Tsunami UDP Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Tsunami_UDP_Protocol"
wikipedia_categories: ["Computer networking", "Internet protocols", "Transport layer protocols"]
related: ["[[QUIC]]", "[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Domain Name System]]", "[[Fast and Secure Protocol]]", "[[Host model]]", "[[Multipurpose Transaction Protocol]]", "[[Named data networking]]", "[[Reliable Data Protocol]]", "[[Reliable Datagram Sockets]]"]
---

# Tsunami UDP Protocol

The Tsunami UDP Protocol is a UDP-based protocol that was developed for high-speed file transfer over network paths that have a high bandwidth-delay product.  Such protocols are needed because standard TCP does not perform well over paths with high bandwidth-delay products. Tsunami was developed at the Advanced Network Management Laboratory of Indiana University. Tsunami effects a file transfer by chunking the file into numbered blocks of 32 kilobyte. Communication between the client and server applications flows over a low bandwidth TCP connection, and the bulk data is transferred over UDP.

## Related

- [[QUIC]]
- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Domain Name System]]
- [[Fast and Secure Protocol]]
- [[Host model]]
- [[Multipurpose Transaction Protocol]]
- [[Named data networking]]
- [[Reliable Data Protocol]]
- [[Reliable Datagram Sockets]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tsunami_UDP_Protocol