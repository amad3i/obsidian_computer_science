---
title: "Host Identity Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Host_Identity_Protocol"
wikipedia_categories: ["Computer network security", "Cryptographic protocols", "IPsec", "Internet protocols", "Multihoming"]
related: ["[[IPsec]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Identifier-Locator Network Protocol]]", "[[Microsoft Point-to-Point Encryption]]", "[[OCSP stapling]]", "[[Online Certificate Status Protocol]]", "[[Publius (publishing system)]]", "[[SCVP]]", "[[Secure Neighbor Discovery]]"]
---

# Host Identity Protocol

The Host Identity Protocol (HIP) is a host identification technology for use on Internet Protocol (IP) networks, such as the Internet. The Internet has two main name spaces, IP addresses and the Domain Name System. HIP separates the end-point identifier and locator roles of IP addresses. It introduces a Host Identity (HI) name space, based on a public key security infrastructure.
The Host Identity Protocol provides secure methods for IP multihoming and mobile computing.
In networks that implement the Host Identity Protocol, all occurrences of IP addresses in applications are eliminated and replaced with cryptographic host identifiers. The cryptographic keys are typically, but not necessarily, self-generated.
The effect of eliminating IP addresses in application and transport layers is a decoupling of the transport layer from the internetworking layer (Internet Layer) in TCP/IP.
HIP was specified in the IETF HIP working group. An Internet Research Task Force (IRTF) HIP research group looks at the broader impacts of HIP.
The working group is chartered to produce Requests for Comments on the "Experimental" track, but it is understood that their quality and security properties should match the standards track requirements. The main purpose for producing Experimental documents instead of standards track ones are the unknown effects that the mechanisms may have on applications and on the Internet in the large.

## Related

- [[IPsec]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Identifier-Locator Network Protocol]]
- [[Microsoft Point-to-Point Encryption]]
- [[OCSP stapling]]
- [[Online Certificate Status Protocol]]
- [[Publius (publishing system)]]
- [[SCVP]]
- [[Secure Neighbor Discovery]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Host_Identity_Protocol