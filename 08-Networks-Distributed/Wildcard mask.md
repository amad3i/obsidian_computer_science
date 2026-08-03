---
title: "Wildcard mask"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Wildcard_mask"
wikipedia_categories: ["IP addresses", "Internet architecture", "Routing"]
related: ["[[Classless Inter-Domain Routing]]", "[[Subnet]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[AS 7007 incident]]", "[[Classful network]]", "[[Default route]]", "[[Echo (communications protocol)]]", "[[Hot-potato routing]]", "[[IEEE 802.1aq]]"]
---

# Wildcard mask

A wildcard mask is a mask of bits that indicates which parts of an IP address are available for examination. In the Cisco IOS, they are used in several places, for example:

To indicate the size of a network or subnet for some routing protocols, such as OSPF.
To indicate what IP addresses should be permitted or denied in access control lists (ACLs).
A wildcard mask can be thought of as an inverted subnet mask. For example, a subnet mask of 255.255.255.0 (11111111.11111111.11111111.000000002) inverts to a wildcard mask of 0.0.0.255 (00000000.00000000.00000000.111111112).
A wild card mask is a matching rule. The rule for a wildcard mask is:

0 means that the equivalent bit must match
1 means that the equivalent bit does not matter
Any wildcard bit-pattern can be masked for examination. For example, a wildcard mask of 0.0.0.254 (00000000.00000000.00000000.111111102) applied to IP address 10.10.10.2 (00001010.00001010.00001010.000000102) will match even-numbered IP addresses 10.10.10.0, 10.10.10.2, 10.10.10.4, 10.10.10.6 etc. Same mask applied to 10.10.10.1 (00001010.00001010.00001010.000000012) will match odd-numbered IP addresses 10.10.10.1, 10.10.10.3, 10.10.10.5 etc.
A network and wildcard mask combination of 1.1.1.1 0.0.0.0 would match an interface configured exactly with 1.1.1.1 only, and nothing else.
Wildcard masks are used in situations where subnet masks may not apply. For example, when two affected hosts fall in different subnets, the use of a wildcard mask will group them together.

## Related

- [[Classless Inter-Domain Routing]]
- [[Subnet]]
- [[AiScaler]]
- [[Any-source multicast]]
- [[AS 7007 incident]]
- [[Classful network]]
- [[Default route]]
- [[Echo (communications protocol)]]
- [[Hot-potato routing]]
- [[IEEE 802.1aq]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Wildcard_mask