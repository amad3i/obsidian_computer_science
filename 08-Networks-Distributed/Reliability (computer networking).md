---
title: "Reliability (computer networking)"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Reliability_(computer_networking)"
wikipedia_categories: ["Network protocols", "Reliability engineering"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Anomaly detection]]", "[[Antifragility]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]"]
---

# Reliability (computer networking)

In computer networking, a reliable protocol is a communication protocol that notifies the sender whether or not the delivery of data to intended recipients was successful.  Reliability is a synonym for assurance, which is the term used by the ITU and ATM Forum, and leads to fault-tolerant messaging.
Reliable protocols typically incur more overhead than unreliable protocols, and as a result, function more slowly and with less scalability. This often is not an issue for unicast protocols, but it may become a problem for reliable multicast protocols.
Transmission Control Protocol (TCP), the main protocol used on the Internet, is a reliable unicast protocol; it provides the abstraction of a reliable byte stream to applications. UDP is an unreliable protocol and is often used in computer games, streaming media or in other situations where speed is an issue and some data loss may be tolerated because of the transitory nature of the data.
Often, a reliable unicast protocol is also connection oriented. For example, TCP is connection oriented, with the virtual-circuit ID consisting of source and destination IP addresses and port numbers. However, some unreliable protocols are connection oriented, such as Asynchronous Transfer Mode and Frame Relay. In addition, some connectionless protocols, such as IEEE 802.11, are reliable.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Anomaly detection]]
- [[Antifragility]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reliability_(computer_networking)