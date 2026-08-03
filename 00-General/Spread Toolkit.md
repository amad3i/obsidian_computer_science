---
title: "Spread Toolkit"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Spread_Toolkit"
wikipedia_categories: ["Middleware"]
related: ["[[ActiveVOS]]", "[[Advanced Message Queuing Protocol]]", "[[Advanced Resource Connector]]", "[[Akka.io]]", "[[Asynchrony (computer programming)]]", "[[Audiokinetic Wwise]]", "[[Ayotle]]", "[[Base One Foundation Component Library]]", "[[Candle Corporation]]", "[[CICS]]"]
---

# Spread Toolkit

The Spread Toolkit is a computer software package that provides a high performance group communication system that is resilient to faults across local and wide area networks. Spread functions as a unified message bus for distributed applications, and provides highly tuned application-level multicast, group communication, and point to point support. Spread services range from reliable messaging to fully ordered messages with delivery guarantees.
The toolkit consists of a messaging server, and client libraries for many software development environments, including C/C++ libraries (with and without thread support), a Java class to be used by applets or applications, and interfaces for Perl, Python, and Ruby.  Interfaces for many other software environments have been provided by third parties.
In typical operation, each computer in a cluster runs its own instance of the Spread server, and client applications connect locally to that server process.  The Spread servers, in turn, communicate with each other to pass messages to subscriber applications.  It can also be configured so that clients distributed across the network all communicate with a Spread server process on one host.
The Spread Toolkit is developed by Spread Concepts LLC, with much support by the Distributed Systems and Networks Lab (DSN) at Johns Hopkins University, and the Experimental Networked Systems Lab at George Washington University.
Partial funding was provided by the Defense Advanced Research Projects Agency (DARPA) and The National Security Agency (NSA).

## Related

- [[ActiveVOS]]
- [[Advanced Message Queuing Protocol]]
- [[Advanced Resource Connector]]
- [[Akka.io]]
- [[Asynchrony (computer programming)]]
- [[Audiokinetic Wwise]]
- [[Ayotle]]
- [[Base One Foundation Component Library]]
- [[Candle Corporation]]
- [[CICS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spread_Toolkit