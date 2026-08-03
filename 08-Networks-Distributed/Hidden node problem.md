---
title: "Hidden node problem"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Hidden_node_problem"
wikipedia_categories: ["IEEE 802.11", "Wireless networking"]
related: ["[[CCMP (cryptography)]]", "[[Complementary code keying]]", "[[Control and Provisioning of Wireless Access Points protocol]]", "[[Direct-sequence spread spectrum]]", "[[Exposed node problem]]", "[[IEEE 802.11ad]]", "[[IEEE 802.11af]]", "[[Morse Micro]]", "[[Temporal Key Integrity Protocol]]", "[[Wired Equivalent Privacy]]"]
---

# Hidden node problem

In wireless networking, the hidden node problem or hidden terminal problem occurs when a node can communicate with a wireless access point (AP), but cannot directly communicate with other nodes that are communicating with that AP. This leads to difficulties in medium access control sublayer since multiple nodes can send data packets to the AP simultaneously, which creates interference at the AP resulting in no packet getting through.
Although some loss of packets is normal in wireless networking, and the higher layers will resend them, if one of the nodes is transferring a lot of large packets over a long period, the other node may get very little goodput.
Practical protocol solutions exist to the hidden node problem. For example, Request To Send/Clear To Send (RTS/CTS) mechanisms where nodes send short packets to request permission of the AP to send longer data packets. As responses from the AP are seen by all the nodes, the nodes can synchronize their transmissions to not interfere. However, the mechanism introduces latency, and the overhead can often be greater than the cost, particularly for short data packets.

## Related

- [[CCMP (cryptography)]]
- [[Complementary code keying]]
- [[Control and Provisioning of Wireless Access Points protocol]]
- [[Direct-sequence spread spectrum]]
- [[Exposed node problem]]
- [[IEEE 802.11ad]]
- [[IEEE 802.11af]]
- [[Morse Micro]]
- [[Temporal Key Integrity Protocol]]
- [[Wired Equivalent Privacy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hidden_node_problem