---
title: "Router alert label"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Router_alert_label"
wikipedia_categories: ["Computer network stubs", "Internet Standards", "MPLS networking", "Network protocols", "Tunneling protocols"]
related: ["[[MPLS-TP]]", "[[T-MPLS]]", "[[Automatic switched-transport network]]", "[[Constraint-based Routing Label Distribution Protocol]]", "[[G.9963]]", "[[G.9970]]", "[[Overlay transport virtualization]]", "[[Available bit rate]]", "[[Bandwidth allocation protocol]]", "[[BatiBUS]]"]
---

# Router alert label

In MPLS, a label with the value of 1 represents the router alert label. This label value is legal anywhere in the label stack except at the bottom. When a received packet contains this label value at the top of the label stack, it is delivered to a local software module for processing. The actual forwarding of the packet is determined by the label beneath it in the stack. However, if the packet is forwarded further, the Router Alert Label should be pushed back onto the label stack before forwarding. The use of this label is analogous to the use of the "Router Alert" option in IPv4 packets. Since this label cannot occur at the bottom of the stack, it is not associated with a particular network-layer protocol.

## Related

- [[MPLS-TP]]
- [[T-MPLS]]
- [[Automatic switched-transport network]]
- [[Constraint-based Routing Label Distribution Protocol]]
- [[G.9963]]
- [[G.9970]]
- [[Overlay transport virtualization]]
- [[Available bit rate]]
- [[Bandwidth allocation protocol]]
- [[BatiBUS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Router_alert_label