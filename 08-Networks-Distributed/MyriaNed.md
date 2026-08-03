---
title: "MyriaNed"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/MyriaNed"
wikipedia_categories: ["Network protocols", "Wireless"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# MyriaNed

MyriaNed is a wireless sensor network (WSN) platform developed by DevLab. It uses an epidemic communication style based on standard radio broadcasting. This approach reflects the way humans interact, which is called gossiping. Messages are sent periodically and received by adjoining neighbours. Each message is repeated and duplicated towards all nodes that span the network; it spreads like a virus (hence the term epidemic communication).
This is a very efficient and robust protocol, mainly for two reasons:

First, the nodes do not need to know who is in their neighbourhood at the time of sending a message, there is no notion of an a-priori planned Routing, data is just shared instantaneously.
Second, the network is implicitly reliable since messages may follow different communication routes in parallel. The loss of a message between two nodes does not mean that the data is lost.
Nodes can be added, removed or may be physically moving without the need to reconfigure the network. The GOSSIP protocol is a self-configuring network solution. The network may even be heterogeneous, where several types of nodes communicate different pieces of information with each other at the same time. This is possible due to the fact that no interpretation of the message content is required in order to be able to forward it to other nodes.
Message communication is fully transparent, providing a seamless communication platform, where new functionality can be added later, without the need to change the installed base. Furthermore, MyriaNed is enabled to update the wireless sensor nodes software by means of “over the air” programming of a deployed network.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MyriaNed