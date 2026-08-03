---
title: "Exposed node problem"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Exposed_node_problem"
wikipedia_categories: ["IEEE 802.11", "Wireless networking"]
related: ["[[CCMP (cryptography)]]", "[[Complementary code keying]]", "[[Control and Provisioning of Wireless Access Points protocol]]", "[[Direct-sequence spread spectrum]]", "[[Hidden node problem]]", "[[IEEE 802.11ad]]", "[[IEEE 802.11af]]", "[[Morse Micro]]", "[[Temporal Key Integrity Protocol]]", "[[Wired Equivalent Privacy]]"]
---

# Exposed node problem

In wireless networks, the exposed node problem occurs when a node is prevented from sending packets to other nodes because of co-channel interference with a neighboring transmitter.  Consider an example of four nodes labeled R1, S1, S2, and R2, where the two receivers (R1, R2) are out of range of each other, yet the two transmitters (S1, S2) in the middle are in range of each other.  Here, if a transmission between S1 and R1 is taking place, node S2 is prevented from transmitting to R2 as it concludes after carrier sense that it will interfere with the transmission by its neighbor S1. However note that R2 could still receive the transmission of S2 without interference because it is out of range of S1.
IEEE 802.11 RTS/CTS mechanism helps to solve this problem only if the nodes are synchronized and packet sizes and data rates are the same for both the transmitting nodes. When a node hears an RTS from a neighboring node, but not the corresponding CTS, that node can deduce that it is an exposed node and is permitted to transmit to other neighboring nodes.
If the nodes are not synchronised (or if the packet sizes are different or the data rates are different) the problem may occur that the sender will not hear the CTS or the ACK during the transmission of data of the second sender.
The exposed node problem is not an issue in cellular networks as the power and distance between cells is controlled to avoid it.

## Related

- [[CCMP (cryptography)]]
- [[Complementary code keying]]
- [[Control and Provisioning of Wireless Access Points protocol]]
- [[Direct-sequence spread spectrum]]
- [[Hidden node problem]]
- [[IEEE 802.11ad]]
- [[IEEE 802.11af]]
- [[Morse Micro]]
- [[Temporal Key Integrity Protocol]]
- [[Wired Equivalent Privacy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Exposed_node_problem