---
title: "Publish–subscribe pattern"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Publish–subscribe_pattern"
wikipedia_categories: ["Architectural pattern (computer science)", "Distributed computing architecture", "Message-oriented middleware", "Software design patterns"]
related: ["[[Multitier architecture]]", "[[Action–domain–responder]]", "[[Active record pattern]]", "[[Bulkhead pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Distributed design patterns]]", "[[Enterprise Integration Patterns]]", "[[Entity component system]]"]
---

# Publish–subscribe pattern

In software architecture, the publish–subscribe pattern (pub/sub) is a messaging pattern in which message senders, called publishers, categorize messages into classes (or topics), and send them without needing to know which components will receive them. Message recipients, called subscribers, express interest in one or more classes and only receive messages in those classes, without needing to know the identity of the publishers.
This pattern decouples the components that produce messages from those that consume them, and supports asynchronous, many-to-many communication. The publish–subscribe model is commonly contrasted with message queue-based and point-to-point messaging models, where producers send messages directly to consumers.
Publish–subscribe is a sibling of the message queue paradigm, and is typically a component of larger message-oriented middleware systems. Many modern messaging frameworks and protocols, such as the Java Message Service (JMS), Apache Kafka, and MQTT, support both the pub/sub and queue-based models.
This pattern provides greater network scalability and supports more dynamic topologies, but can make it harder to modify the publisher’s logic or the structure of the published data. Compared to synchronous patterns like RPC and point-to-point messaging, publish–subscribe provides the highest level of decoupling among architectural components. However, it can also lead to semantic or format coupling between publishers and subscribers, which may cause systems to become entangled or brittle over time.

## Related

- [[Multitier architecture]]
- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Bulkhead pattern]]
- [[Data access object]]
- [[Data mapper pattern]]
- [[Data transfer object]]
- [[Distributed design patterns]]
- [[Enterprise Integration Patterns]]
- [[Entity component system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Publish–subscribe_pattern