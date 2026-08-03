---
title: "IP traceback"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IP_traceback"
wikipedia_categories: ["Internet architecture"]
related: ["[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[Anycast]]", "[[Application-layer framing]]", "[[Application-Layer Protocol Negotiation]]", "[[AS 7007 incident]]", "[[Authenticated Received Chain]]"]
---

# IP traceback

IP traceback is any method for reliably determining the origin of a packet on the Internet. The IP protocol does not provide for the authentication of the source IP address of an IP packet, enabling the source address to be falsified in a strategy called IP address spoofing, and creating potential internet security and stability problems.
Use of false source IP addresses allows denial-of-service attacks (DoS) or one-way attacks (where the response from the victim host is so well known that return packets need not be received to continue the attack). IP traceback is critical for identifying sources of attacks and instituting protection measures for the Internet. Most existing approaches to this problem have been tailored toward DoS attack detection. Such solutions require high numbers of packets to converge on the attack path(s).

## Related

- [[6bone]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]
- [[AiScaler]]
- [[Any-source multicast]]
- [[Anycast]]
- [[Application-layer framing]]
- [[Application-Layer Protocol Negotiation]]
- [[AS 7007 incident]]
- [[Authenticated Received Chain]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IP_traceback