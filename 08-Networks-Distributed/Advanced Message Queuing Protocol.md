---
title: "Advanced Message Queuing Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Advanced_Message_Queuing_Protocol"
wikipedia_categories: ["Application layer protocols", "Inter-process communication", "Message-oriented middleware", "Middleware", "Open standards"]
related: ["[[Web Application Messaging Protocol]]", "[[Asynchrony (computer programming)]]", "[[Client–server model]]", "[[Comparison of MQTT implementations]]", "[[List of products that support SMB]]", "[[Message broker]]", "[[Message-oriented middleware]]", "[[Messaging pattern]]", "[[Microsoft BizTalk Server]]", "[[MQTT]]"]
---

# Advanced Message Queuing Protocol

The Advanced Message Queuing Protocol (AMQP) is an open standard application layer protocol for message-oriented middleware. The defining features of AMQP are message orientation, queuing, routing (including point-to-point and publish-and-subscribe), reliability and security.
AMQP mandates the behavior of the messaging provider and client to the extent that implementations from different vendors are interoperable, in the same way as SMTP, HTTP, FTP, etc. have created interoperable systems. Previous standardizations of middleware have happened at the API level (e.g. JMS) and were focused on standardizing programmer interaction with different middleware implementations, rather than on providing interoperability between multiple implementations. Unlike JMS, which defines an API and a set of behaviors that a messaging implementation must provide, AMQP is a wire-level protocol. A wire-level protocol is a description of the format of the data that is sent across the network as a stream of bytes. Consequently, any tool that can create and interpret messages that conform to this data format can interoperate with any other compliant tool irrespective of implementation language.

## Related

- [[Web Application Messaging Protocol]]
- [[Asynchrony (computer programming)]]
- [[Client–server model]]
- [[Comparison of MQTT implementations]]
- [[List of products that support SMB]]
- [[Message broker]]
- [[Message-oriented middleware]]
- [[Messaging pattern]]
- [[Microsoft BizTalk Server]]
- [[MQTT]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Advanced_Message_Queuing_Protocol