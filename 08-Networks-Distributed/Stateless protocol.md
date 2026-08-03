---
title: "Stateless protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Stateless_protocol"
wikipedia_categories: ["Network protocols", "Servers (computing)"]
related: ["[[Common Gateway Interface]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[AiScaler]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[Application server]]", "[[ARCNET]]"]
---

# Stateless protocol

A stateless protocol is a communication protocol in which the receiver does not retain session state from previous requests. The sender transfers relevant session state to the receiver in such a way that every request can be understood in isolation, without reference to session state from previous requests. 
In contrast, a stateful protocol is a communication protocol in which the receiver may retain session state from previous requests.
In computer networks, examples of stateless protocols include the Internet Protocol (IP), which is the foundation for the Internet, and the Hypertext Transfer Protocol (HTTP), which is the foundation of the World Wide Web. Examples of stateful protocols include the Transmission Control Protocol (TCP) and the File Transfer Protocol (FTP).
Stateless protocols have superior visibility, reliability, and scalability properties. Visibility is improved because a monitoring system does not have to look beyond a single request in order to determine its full nature. Reliability is improved because it eases the task of recovering from failures such as packet loss. Scalability is improved because not having to store session state between requests allows the server to quickly free resources and further simplifies implementation. The disadvantage of stateless protocols is that they may decrease network performance by increasing the repetitive data sent in a series of requests, since that data is not retained or reused at the receiver.

## Related

- [[Common Gateway Interface]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[AiScaler]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[Application server]]
- [[ARCNET]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stateless_protocol