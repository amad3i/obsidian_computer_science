---
title: "Robust random early detection"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Robust_random_early_detection"
wikipedia_categories: ["Computer network security", "Denial-of-service attacks", "Network performance", "Packets (information technology)"]
related: ["[[Black hole (networking)]]", "[[Broadcast storm]]", "[[DDoS mitigation]]", "[[Deep packet inspection]]", "[[Interest Flooding Attack]]", "[[Science DMZ Network Architecture]]", "[[Stateful firewall]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Adaptive quality of service multi-hop routing]]"]
---

# Robust random early detection

Robust random early detection (RRED) is a queueing discipline for a network scheduler. The existing random early detection (RED) algorithm and its variants are found vulnerable to emerging attacks, especially the Low-rate Denial-of-Service attacks (LDoS). Experiments have confirmed that the existing RED-like algorithms are notably vulnerable under LDoS attacks due to the oscillating TCP queue size caused by the attacks. 
The Robust RED (RRED) algorithm was proposed to improve the TCP throughput against LDoS attacks. The basic idea behind the RRED is to detect and filter out attack packets before a normal RED algorithm is applied to incoming flows. RRED algorithm can significantly improve the performance of TCP under Low-rate denial-of-service attacks.

## Related

- [[Black hole (networking)]]
- [[Broadcast storm]]
- [[DDoS mitigation]]
- [[Deep packet inspection]]
- [[Interest Flooding Attack]]
- [[Science DMZ Network Architecture]]
- [[Stateful firewall]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Adaptive quality of service multi-hop routing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Robust_random_early_detection