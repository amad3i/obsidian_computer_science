---
title: "QUIC"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/QUIC"
wikipedia_categories: ["Computer networking", "Internet properties established in 2012", "Internet protocols", "Transport layer protocols"]
related: ["[[Tsunami UDP Protocol]]", "[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Domain Name System]]", "[[Fast and Secure Protocol]]", "[[Host model]]", "[[Multipurpose Transaction Protocol]]", "[[Named data networking]]", "[[Reliable Data Protocol]]", "[[Reliable Datagram Sockets]]"]
---

# QUIC

QUIC () is a general-purpose transport layer network protocol initially designed by Jim Roskind at Google. It was first implemented and deployed in 2012 and was publicly announced in 2013 as experimentation broadened. It was also described at an IETF meeting. QUIC is supported by major web browsers, including Chrome, Edge, Firefox, and Safari. In Chrome, QUIC is used by more than half of all connections to Google's servers.
QUIC improves performance of connection-oriented web applications that previously relied on Transmission Control Protocol (TCP). It does this by establishing a number of multiplexed connections between two endpoints using User Datagram Protocol (UDP), and it is designed to obsolete TCP at the transport layer for many applications. Although its name was initially proposed as an acronym for Quick UDP Internet Connections, in IETF's use of the word QUIC is not an acronym; it is simply the name of the protocol. 
QUIC works hand-in-hand with HTTP/3's multiplexed connections, allowing multiple streams of data to reach all the endpoints independently, and hence independent of packet losses involving other streams. In contrast, HTTP/2, which is carried over TCP, can suffer head-of-line-blocking delays if multiple streams are multiplexed on a TCP connection and any of the TCP packets on that connection are delayed or lost.
QUIC's secondary goals include reduced connection and transport latency, and bandwidth estimation in each direction to avoid congestion. It also moves congestion control algorithms into the user space at both endpoints, rather than the kernel space, which is claimed to allow these algorithms to improve more rapidly. Additionally, the protocol can be extended with forward error correction (FEC) to further improve performance when errors are expected. It is designed with the intention of avoiding protocol ossification.
In June 2015, an Internet Draft of a specification for QUIC was submitted to the IETF for standardization. A QUIC working group was established in 2016. In October 2018, the IETF's HTTP and QUIC Working Groups jointly decided to call the HTTP mapping over QUIC "HTTP/3" in advance of making it a worldwide standard. In May 2021, the IETF standardized QUIC in RFC 9000, supported by RFC 8999, 9001 and 9002. DNS-over-QUIC is another application.

## Related

- [[Tsunami UDP Protocol]]
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

- Wikipedia: https://en.wikipedia.org/wiki/QUIC