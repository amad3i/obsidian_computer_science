---
title: "Secure Neighbor Discovery"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Secure_Neighbor_Discovery"
wikipedia_categories: ["Computer network stubs", "Cryptographic protocols", "IPv6", "Internet protocols", "Link protocols"]
related: ["[[Metro Ring Protocol]]", "[[Neighbor Discovery Protocol]]", "[[BGP Monitoring Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Compiled Wireless Markup Language]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[Fast Local Internet Protocol]]", "[[First-hop redundancy protocol]]"]
---

# Secure Neighbor Discovery

The Secure Neighbor Discovery (SEND) protocol is a security extension of the Neighbor Discovery Protocol (NDP) in IPv6 defined in RFC 3971 and updated by RFC 6494.
The Neighbor Discovery Protocol (NDP) is responsible in IPv6 for discovery of other network nodes on the local link, to determine the link layer addresses of other nodes, and to find available routers, and maintain reachability information about the paths to other active neighbor nodes (RFC 4861). NDP is insecure and susceptible to malicious interference. It is the intent of SEND to provide an alternate mechanism for securing NDP with a cryptographic method that is independent of IPsec, the original and inherent method of securing IPv6 communications.
SEND uses Cryptographically Generated Addresses (CGA) and other new NDP options for the ICMPv6 packet types used in NDP.
SEND was updated to use the Resource Public Key Infrastructure (RPKI) by RFC 6494 and RFC 6495 which define the use of a SEND Certificate Profile utilizing a modified RFC 6487 RPKI Certificate Profile which must include a single RFC 3779 IP Address Delegation extension.
There have been concerns with algorithm agility vis-à-vis attacks on hash functions used by SEND expressed in RFC 6273, as CGA currently uses the SHA-1 hash algorithm and PKIX certificates and does not provide support for alternative hash algorithms.

## Related

- [[Metro Ring Protocol]]
- [[Neighbor Discovery Protocol]]
- [[BGP Monitoring Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Compiled Wireless Markup Language]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[Fast Local Internet Protocol]]
- [[First-hop redundancy protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Secure_Neighbor_Discovery