---
title: "STREAMS"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/STREAMS"
wikipedia_categories: ["Computer networking", "Inter-process communication", "UNIX System V", "Unix"]
related: ["[[Pipeline (Unix)]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Advanced Message Queuing Protocol]]", "[[Application Defined Network]]", "[[ARexx]]", "[[Asynchrony (computer programming)]]", "[[Blocking (computing)]]", "[[Client–server model]]", "[[CMS Pipelines]]", "[[Common Object Request Broker Architecture]]"]
---

# STREAMS

In computer networking, STREAMS is the native framework in Unix System V for implementing character device drivers, network protocols, and inter-process communication. In this framework, a stream is a chain of coroutines that pass messages between a program and a device driver (or between a pair of programs). STREAMS originated in Version 8 Research Unix, as Streams (not capitalized).
STREAMS's design is a modular architecture for implementing full-duplex I/O between kernel and device drivers. Its most frequent uses have been in developing terminal I/O (line discipline) and networking subsystems. In System V Release 4, the entire terminal interface was reimplemented using STREAMS. An important concept in STREAMS is the ability to push drivers –  custom code modules which can modify the functionality of a network interface or other device –  together to form a stack. Several of these drivers can be chained together in order.

## Related

- [[Pipeline (Unix)]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Advanced Message Queuing Protocol]]
- [[Application Defined Network]]
- [[ARexx]]
- [[Asynchrony (computer programming)]]
- [[Blocking (computing)]]
- [[Client–server model]]
- [[CMS Pipelines]]
- [[Common Object Request Broker Architecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/STREAMS