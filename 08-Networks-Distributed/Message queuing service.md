---
title: "Message queuing service"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Message_queuing_service"
wikipedia_categories: ["Cloud computing", "Message-oriented middleware"]
related: ["[[Abiquo Enterprise Edition]]", "[[Advanced Message Queuing Protocol]]", "[[AI data center]]", "[[AI infrastructure]]", "[[Alibaba Cloud]]", "[[Amaryllo]]", "[[Amazon Elastic Compute Cloud]]", "[[Amazon Kinesis]]", "[[Ampere Computing]]", "[[Apache CarbonData]]"]
---

# Message queuing service

A message queueing service is a message-oriented middleware or MOM deployed in a compute cloud using software as a service model. Service subscribers access queues and or topics to exchange data using point-to-point or publish and subscribe patterns.
It's important to differentiate between event-driven and message-driven (aka queue driven) services: Event-driven services (e.g. AWS SNS) are decoupled from their consumers. Whereas queue / message driven services (e.g. AWS SQS) are coupled with their consumers.
Message queues can be a good buffer to handle spiky workloads but they have a finite capacity. According to Gregor Hohpe, message queues require proper mechanisms (aka flow controls) to avoid filling the queue beyond its manageable capacity and to keep the system stable.

## Related

- [[Abiquo Enterprise Edition]]
- [[Advanced Message Queuing Protocol]]
- [[AI data center]]
- [[AI infrastructure]]
- [[Alibaba Cloud]]
- [[Amaryllo]]
- [[Amazon Elastic Compute Cloud]]
- [[Amazon Kinesis]]
- [[Ampere Computing]]
- [[Apache CarbonData]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Message_queuing_service