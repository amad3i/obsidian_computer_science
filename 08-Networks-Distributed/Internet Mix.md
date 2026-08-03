---
title: "Internet Mix"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Internet_Mix"
wikipedia_categories: ["Internet architecture"]
related: ["[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[Anycast]]", "[[Application-layer framing]]", "[[Application-Layer Protocol Negotiation]]", "[[AS 7007 incident]]", "[[Authenticated Received Chain]]"]
---

# Internet Mix

Internet Mix or IMIX refers to typical Internet traffic passing some network equipment such as routers, switches or firewalls. When measuring equipment performance using an IMIX of packets the performance is assumed to resemble what can be seen in real-world conditions. 
Network equipment that performs complex manipulation of packets, such as firewalls or VPN routers, often have non-wire rate performance and as such it can not deliver wire rate performance on small 64 byte packets, this is easier at 1500 byte packets - but none of these packet sizes resemble actual traffic seen on the Internet over some time. 
The IMIX traffic profiles are used by network equipment vendors to simulate real-world traffic patterns and packet distributions. IMIX profiles are based on statistical sampling done on Internet routers, and are published in various levels of granularity, such as simple and complete. 
Although the actual Internet traffic mix has changed over time, the standardized IMIX profiles used for testing have not been updated accordingly because the IMIX test results need to be comparable. 
Mix profiles exist for IPv4, TCP, VPN (IPsec) and IPv6 traffic, distributions are similar but frame sizes vary given the different overhead and upper layer limitations on MTU. 
Here is an illustration of the Simple IMIX, a mix often used by firewall vendors showing IMIX throughput performance in their data sheets (along with the optimal test conditions throughput performance):

Here is an illustration of the optimal test conditions IMIX used by some firewall vendors showing only theoretical throughput performance in their data sheets:

Early scholarly studies in 2004 indicated that TCP traffic in particular exhibits a bimodal distribution with spikes around minimum-sized packets (less than 100 bytes) and Ethernet MTU (more than 1400 bytes). Later studies confirmed this for backbone and enterprise networks.

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

- Wikipedia: https://en.wikipedia.org/wiki/Internet_Mix