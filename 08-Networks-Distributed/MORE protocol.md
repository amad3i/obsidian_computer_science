---
title: "MORE protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/MORE_protocol"
wikipedia_categories: ["Wireless networking"]
related: ["[[2016 United States wireless spectrum auction]]", "[[Ad hoc wireless distribution service]]", "[[Air2Web]]", "[[AirHop Communications]]", "[[Andrea Goldsmith (engineer)]]", "[[Augmented tree-based routing]]", "[[Backhaul (telecommunications)]]", "[[Barker code]]", "[[Base station]]", "[[Base transceiver station]]"]
---

# MORE protocol

MORE, which stands for MAC independent Opportunistic Routing, is an opportunistic routing protocol designed for wireless mesh networks.  The protocol removes the dependency that other opportunistic routing protocols, such as ExOR and SOAR have on the MAC layer. Both of these protocols make use of a scheduler, to co-ordinate transmission among the nodes. Only one node transmits at a given point of time and all the other nodes listen to this. The nodes that listen remove the packets which they have queued for retransmission. This ensures that the same packet is not redundantly retransmitted by different nodes.
MORE makes use of network encoding techniques and brings about spatial re-use by allowing all the nodes to transmit at the same time. Given a file, the source node breaks up the file into K packets. The number of packets each file is divided into varies. The uncoded packets are called "native packets". The source node then creates a linear combination of K packets and forwards them. The code vector represents the random co-efficients chosen by the node to perform encoding. The source also attaches a MORE header to each packet along with a forwarding list. The forwarders listen to the transmission of the source node. If the node that listens to this packet is in the forwarding list, it checks if the packet has any new information which are called as innovative packets. If the packet is innovative, it performs a linear recombination of the packets. This is essentially the linear recombination of the native packets again. The node ignores all non-innovative packets. The destination receives the packets and checks for innovative-ness. Upon receiving K innovative packets, it sends back ACK to the source and continues decoding the packets. The intermediate nodes hear this ACK and stop further transmission followed by the purging of packets in the buffer.

## Related

- [[2016 United States wireless spectrum auction]]
- [[Ad hoc wireless distribution service]]
- [[Air2Web]]
- [[AirHop Communications]]
- [[Andrea Goldsmith (engineer)]]
- [[Augmented tree-based routing]]
- [[Backhaul (telecommunications)]]
- [[Barker code]]
- [[Base station]]
- [[Base transceiver station]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MORE_protocol