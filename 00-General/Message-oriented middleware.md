---
title: "Message-oriented middleware"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Message-oriented_middleware"
wikipedia_categories: ["Enterprise application integration", "Message-oriented middleware", "Middleware", "Systems engineering"]
related: ["[[Microsoft BizTalk Server]]", "[[Virtuoso Universal Server]]", "[[Advanced Message Queuing Protocol]]", "[[Comparison of business integration software]]", "[[Enterprise Integration Patterns]]", "[[Enterprise service bus]]", "[[Message broker]]", "[[Middleware (distributed applications)]]", "[[Web Application Messaging Protocol]]", "[[ActiveVOS]]"]
---

# Message-oriented middleware

Message-oriented middleware (MOM) is software or hardware infrastructure supporting sending and receiving messages between distributed systems. Message-oriented middleware is in contrast to streaming-oriented middleware where data is communicated as a sequence of bytes with no explicit message boundaries. Note that streaming protocols are almost always built above protocols using discrete messages such as frames (Ethernet), datagrams (UDP), packets (IP), cells (ATM), et al. 
MOM allows application modules to be distributed over heterogeneous platforms and reduces the complexity of developing applications that span multiple operating systems and network protocols. The middleware creates a distributed communications layer that insulates the application developer from the details of the various operating systems and network interfaces. Application programming interfaces (APIs) that extend across diverse platforms and networks are typically provided by MOM.
This middleware layer allows software components (applications, servlets, and other components) that have been developed independently and might run on different networked platforms to interact with one another. Applications distributed on different network nodes use the application interface to communicate. In addition, by providing an administrative interface, this new, virtual system of interconnected applications can be made fault tolerant and secure.
MOM provides software elements that reside in all communicating components of a client/server architecture and typically support asynchronous calls between the client and server applications. MOM reduces the involvement of application developers with the complexity of the master-slave nature of the client/server mechanism.

## Related

- [[Microsoft BizTalk Server]]
- [[Virtuoso Universal Server]]
- [[Advanced Message Queuing Protocol]]
- [[Comparison of business integration software]]
- [[Enterprise Integration Patterns]]
- [[Enterprise service bus]]
- [[Message broker]]
- [[Middleware (distributed applications)]]
- [[Web Application Messaging Protocol]]
- [[ActiveVOS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Message-oriented_middleware