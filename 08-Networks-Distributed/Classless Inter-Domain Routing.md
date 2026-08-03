---
title: "Classless Inter-Domain Routing"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing"
wikipedia_categories: ["IP addresses", "Internet Standards", "Internet architecture", "Routing"]
related: ["[[Subnet]]", "[[Wildcard mask]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[AS 7007 incident]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Classful network]]", "[[Default route]]", "[[Differentiated services]]"]
---

# Classless Inter-Domain Routing

Classless Inter-Domain Routing (CIDR pronounced "cider" or  SID-ər) is a method for allocating IP addresses for IP routing. The Internet Engineering Task Force introduced CIDR in 1993 to replace the previous classful network addressing architecture on the Internet. Its goal was to slow the growth of routing tables on routers across the Internet, and to help slow the rapid exhaustion of IPv4 addresses.
IP addresses are described as consisting of two groups of bits in the address: the most significant bits are the network prefix, which identifies a whole network or subnet, and the least significant set forms the host identifier, which specifies a particular interface of a host on that network. This division is used as the basis of traffic routing between IP networks and for address allocation policies.
Whereas classful network design for IPv4 sized the network prefix as one or more eight-bit groups, resulting in the blocks of Class A, B, or C addresses, under CIDR address space, is allocated to Internet service providers (ISPs) and end users on any address-bit boundary. In IPv6, however, the interface identifier has a fixed size of 64 bits by convention, and smaller subnets are never allocated to end users.
CIDR is based on variable-length subnet masking (VLSM), in which network prefixes have variable length as opposed to the fixed-length prefixing of the previous classful network design. The main benefit of this is that it grants finer control of the sizes of subnets allocated to organizations, hence slowing the exhaustion of IPv4 addresses from the allocation of larger subnets than needed. CIDR gave rise to a new way of writing IP addresses known as CIDR notation, in which an IP address is followed by a suffix indicating the number of bits of the prefix. Some examples of CIDR notation are the addresses 192.0.2.0/24 for IPv4 and 2001:db8::/32 for IPv6. Blocks of addresses having contiguous prefixes may be aggregated as supernets, reducing the number of entries in the global routing table.

## Related

- [[Subnet]]
- [[Wildcard mask]]
- [[AiScaler]]
- [[Any-source multicast]]
- [[AS 7007 incident]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Classful network]]
- [[Default route]]
- [[Differentiated services]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing