---
title: "Security Parameters Index"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Security_Parameters_Index"
wikipedia_categories: ["IPsec", "Internet protocols", "Internet stubs"]
related: ["[[Asynchronous Layered Coding]]", "[[Border Gateway Multicast Protocol]]", "[[Endpoint Handlespace Redundancy Protocol]]", "[[Extensible Name Service]]", "[[High Frequency Internet Protocol]]", "[[Host Identity Protocol]]", "[[Internet Imaging Protocol]]", "[[Internet Open Trading Protocol]]", "[[IPFC]]", "[[IPsec]]"]
---

# Security Parameters Index

The Security Parameter Index (SPI) is an identification tag added to the header while using IPsec for tunneling the IP traffic.  This tag helps the kernel discern between two traffic streams where different encryption rules and algorithms may be in use.
The SPI (as per RFC 4301) is a required part of an IPsec Security Association (SA) because it enables the receiving system to select the SA under which a received packet will be processed. An SPI has only local significance, since it is defined by the creator of the SA; an SPI is generally viewed as an opaque bit string. However, the creator of an SA may interpret the bits in an SPI to facilitate local processing.
This works like port numbers in TCP and UDP connections. What it means is that there could be different SAs used to provide security to one connection. An SA could therefore act as a set of rules.
Carried in Encapsulating Security Payload (ESP) header or Authentication Header (AH), its length is 32 bits.

## Related

- [[Asynchronous Layered Coding]]
- [[Border Gateway Multicast Protocol]]
- [[Endpoint Handlespace Redundancy Protocol]]
- [[Extensible Name Service]]
- [[High Frequency Internet Protocol]]
- [[Host Identity Protocol]]
- [[Internet Imaging Protocol]]
- [[Internet Open Trading Protocol]]
- [[IPFC]]
- [[IPsec]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Security_Parameters_Index