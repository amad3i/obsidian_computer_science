---
title: "Kqueue"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Kqueue"
wikipedia_categories: ["BSD software", "DragonFly BSD", "Events (computing)", "FreeBSD", "MacOS", "NetBSD", "OpenBSD", "Operating system APIs"]
related: ["[[Busdma]]", "[[ALTQ]]", "[[Pfsync]]", "[[Soft updates]]", "[[Sysctl]]", "[[Vinum volume manager]]", "[[FreeBSD jail]]", "[[Vkernel]]", "[[Access method]]", "[[Apple File System]]"]
---

# Kqueue

Kqueue is a scalable event notification interface introduced in FreeBSD 4.1 in July 2000, also supported in NetBSD, OpenBSD, DragonFly BSD, and macOS. Kqueue was originally authored in 2000 by Jonathan Lemon, then involved with the FreeBSD Core Team. Kqueue makes it possible for software like nginx to solve the c10k problem. The term "kqueue" refers to its function as a "kernel event queue"
Kqueue provides efficient input and output event pipelines between the kernel and userland. Thus, it is possible to modify event filters as well as receive pending events while using only a single system call to kevent(2) per main event loop iteration. This contrasts with older traditional polling system calls such as poll(2) and select(2) which are less efficient, especially when polling for events on numerous file descriptors.
Kqueue not only handles file descriptor events but is also used for various other notifications such as file modification monitoring, signals, asynchronous I/O events (AIO), child process state change monitoring, and timers which support nanosecond resolution. Furthermore, kqueue provides a way to use user-defined events in addition to the ones provided by the kernel.
Some other operating systems which traditionally only supported select(2) and poll(2) also currently provide more efficient polling alternatives, such as epoll on Linux and I/O completion ports on Windows and Solaris.
libkqueue is a user space implementation of kqueue(2), which translates calls to an operating system's native backend event mechanism.

## Related

- [[Busdma]]
- [[ALTQ]]
- [[Pfsync]]
- [[Soft updates]]
- [[Sysctl]]
- [[Vinum volume manager]]
- [[FreeBSD jail]]
- [[Vkernel]]
- [[Access method]]
- [[Apple File System]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kqueue