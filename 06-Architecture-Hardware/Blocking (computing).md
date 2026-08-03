---
title: "Blocking (computing)"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Blocking_(computing)"
wikipedia_categories: ["Computing terminology", "Input/output", "Inter-process communication", "Operating system stubs", "Scheduling (computing)"]
related: ["[[Rendezvous (Plan 9)]]", "[[Streaming data]]", "[[Address space]]", "[[Advanced Message Queuing Protocol]]", "[[Application posture]]", "[[ARexx]]", "[[Asynchrony (computer programming)]]", "[[Client–server model]]", "[[CMS Pipelines]]", "[[Common Object Request Broker Architecture]]"]
---

# Blocking (computing)

In computing, a process that is blocked is waiting for some event, such as a resource becoming available or the completion of an I/O operation.
Once the event occurs for which the process is waiting ("is blocked on"), the process is advanced from blocked state to an imminent one, such as runnable.
In a multitasking computer system, individual tasks, or threads of execution, must share the resources of the system. Shared resources include: the CPU, network and network interfaces, memory and disk.
When one task is using a resource, it is generally not possible, or desirable, for another task to access it. The techniques of mutual exclusion are used to prevent this concurrent use. When the other task is blocked, it is unable to execute until the first task has finished using the shared resource.
Programming languages and scheduling algorithms are designed to minimize the over-all effect of blocking. A process that blocks may prevent local work-tasks from progressing. In this case "blocking" often is seen as not wanted. However, such work-tasks may instead have been assigned to independent processes, where halting one has little to no effect on the others, since scheduling will continue. An example is "blocking on a channel" where passively waiting for the other part (i.e. no polling or spin loop) is part of the semantics of channels. Correctly engineered, any of these may be used to implement reactive systems.
Deadlock means that processes pathologically wait for each other in a circle. As such it is not directly associated with blocking.

## Related

- [[Rendezvous (Plan 9)]]
- [[Streaming data]]
- [[Address space]]
- [[Advanced Message Queuing Protocol]]
- [[Application posture]]
- [[ARexx]]
- [[Asynchrony (computer programming)]]
- [[Client–server model]]
- [[CMS Pipelines]]
- [[Common Object Request Broker Architecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Blocking_(computing)