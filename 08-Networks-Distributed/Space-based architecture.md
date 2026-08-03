---
title: "Space-based architecture"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Space-based_architecture"
wikipedia_categories: ["Cluster computing", "Distributed computing architecture", "Distributed data storage", "Grid computing", "Middleware"]
related: ["[[Dynamic infrastructure]]", "[[MOSIX]]", "[[OMII-UK]]", "[[Oracle Grid Engine]]", "[[ProActive]]", "[[RCUDA]]", "[[Slurm Workload Manager]]", "[[Supercomputer]]", "[[Virtuoso Universal Server]]", "[[Volunteer computing]]"]
---

# Space-based architecture

A space-based architecture (SBA) is an approach to distributed computing systems where the various components interact with each other by exchanging tuples or entries via one or more shared spaces. This is contrasted with the more common message queuing service approaches where the various components interact with each other by exchanging messages via a message broker. In a sense, both approaches exchange messages with some central agent, but how they exchange messages is very distinctive.
An analogy might be where a message broker is like an academic conference, where each presenter has the stage, and presents in the order they are scheduled; whereas a tuple space is like an unconference, where all participants can write on a common whiteboard concurrently, and all can see it at the same time.

Tuple spaces
each space is like a 'channel' in a message broker system that components can choose to interact with
components can write a 'tuple' or 'entry' into a space, while other components can read entries/tuples from the space, but using more powerful mechanisms than message brokers
writing entries to a space is generally not ordered as in a message broker, but can be if necessary
designing applications using this approach is less intuitive to most people, and can present more cognitive load to appreciate and exploit
Message brokers
each broker typically supports multiple 'channels' that components can choose to interact with
components write 'messages' to a channel, while other components read messages from the channel
writing messages to a channel is generally in order, where they are generally read out in the same order
designing applications using this approach is more intuitive to most people, sort of the way that NoSQL databases are more intuitive than SQL
A key goal of both approaches is to create loosely-coupled systems that minimize configuration, especially shared knowledge of who does what, leading to the objectives of better availability, resilience, scalability, etc.
More specifically, an SBA is a distributed-computing architecture for achieving linear scalability of stateful, high-performance applications using the tuple space paradigm. It follows many of the principles of representational state transfer (REST), service-oriented architecture (SOA) and event-driven architecture (EDA), as well as elements of grid computing. With a space-based architecture, applications are built out of a set of self-sufficient units, known as processing-units (PU). These units are independent of each other, so that the application can scale by adding more units.
The SBA model is closely related to other patterns that have been proved successful in addressing the application scalability challenge, such as shared nothing architecture (SN), used by Google, Amazon.com and other well-known companies. The model has also been applied by many firms in the securities industry for implementing scalable electronic securities trading applications.

## Related

- [[Dynamic infrastructure]]
- [[MOSIX]]
- [[OMII-UK]]
- [[Oracle Grid Engine]]
- [[ProActive]]
- [[RCUDA]]
- [[Slurm Workload Manager]]
- [[Supercomputer]]
- [[Virtuoso Universal Server]]
- [[Volunteer computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Space-based_architecture