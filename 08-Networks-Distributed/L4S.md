---
title: "L4S"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/L4S"
wikipedia_categories: ["Internet protocols", "Network performance", "Queue management", "TCP congestion control"]
related: ["[[Scalable TCP]]", "[[WAN optimization]]", "[[Zeta-TCP]]", "[[Adaptive quality of service multi-hop routing]]", "[[AiScaler]]", "[[ALTQ]]", "[[Application-layer framing]]", "[[Application-Layer Protocol Negotiation]]", "[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]"]
---

# L4S

L4S (for Low Latency, Low Loss and Scalable Throughput) is an IETF network protocol and congestion control technology designed to simultaneously lower network latency and packet loss rates by reducing bufferbloat throughout the Internet, while preserving network throughput. It uses novel congestion control mechanisms to reduce queuing in the network.  
L4S effectively introduces new rules for compliant endpoints and their traffic, giving L4S traffic preferential treatment in exchange for L4S endpoints cooperating by using improved congestion control algorithms. It has the remarkable property of not only improving performance for L4S traffic, but also improving performance for non-L4S traffic sharing the same infrastructure.
L4S has the advantage that it can start to provide incremental latency and throughput improvements through patchwork deployment by individual network operators without having to be adopted throughout the entire Internet, thus providing an incentive for early adopters.

## Related

- [[Scalable TCP]]
- [[WAN optimization]]
- [[Zeta-TCP]]
- [[Adaptive quality of service multi-hop routing]]
- [[AiScaler]]
- [[ALTQ]]
- [[Application-layer framing]]
- [[Application-Layer Protocol Negotiation]]
- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/L4S