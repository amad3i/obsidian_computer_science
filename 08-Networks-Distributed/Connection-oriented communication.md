---
title: "Connection-oriented communication"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Connection-oriented_communication"
wikipedia_categories: ["Computer networking", "Internet architecture", "Internet protocols", "Network protocols"]
related: ["[[Connectionless communication]]", "[[Domain Name System]]", "[[BEEP]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Constrained Shortest Path First]]", "[[Decentralized autonomous organization]]", "[[Forward-confirmed reverse DNS]]", "[[GPSoverIP]]", "[[Host model]]"]
---

# Connection-oriented communication

In telecommunications and computer networking, connection-oriented communication is a communication protocol where a communication session or a semi-permanent connection is established before any useful data can be transferred. The established connection ensures that data is delivered in the correct order to the upper communication layer. The alternative is called connectionless communication, such as the datagram mode communication used by Internet Protocol (IP) and User Datagram Protocol (UDP), where data may be delivered out of order, since different network packets are routed independently and may be delivered over different paths.
Connection-oriented communication may be implemented with a circuit switched connection, or a packet-mode virtual circuit connection. In the latter case, it may use either a transport layer virtual circuit protocol such as the Transmission Control Protocol (TCP) protocol, allowing data to be delivered in order. Although the lower-layer switching is connectionless, or it may be a data link layer or network layer switching mode, where all data packets belonging to the same traffic stream are delivered over the same path, and traffic flows are identified by some connection identifier reducing the overhead of routing decisions on a packet-by-packet basis for the network.
Connection-oriented protocol services are often, but not always, reliable network services that provide acknowledgment after successful delivery and automatic repeat request functions in case of missing or corrupted data. Asynchronous Transfer Mode (ATM), Frame Relay and Multiprotocol Label Switching (MPLS) are examples of connection-oriented unreliable protocols. Simple Mail Transfer Protocol (SMTP) is an example of a connection-oriented protocol in which, if a message is not delivered, an error report is sent to the sender, making it a reliable protocol. Because they can keep track of a conversation, connection-oriented protocols are sometimes described as stateful.

## Related

- [[Connectionless communication]]
- [[Domain Name System]]
- [[BEEP]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Constrained Shortest Path First]]
- [[Decentralized autonomous organization]]
- [[Forward-confirmed reverse DNS]]
- [[GPSoverIP]]
- [[Host model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Connection-oriented_communication