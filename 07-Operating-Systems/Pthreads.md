---
title: "Pthreads"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Pthreads"
wikipedia_categories: ["C POSIX library", "Parallel computing", "Threads (computing)"]
related: ["[[Micro-thread (multi-core)]]", "[[Multithreading (computer architecture)]]", "[[Native POSIX Thread Library]]", "[[Single instruction, multiple threads]]", "[[Task parallelism]]", "[[Thread pool]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]"]
---

# Pthreads

In computing, POSIX Threads, commonly known as pthreads (after its header <pthread.h>), is an execution model that exists independently from a programming language, as well as a parallel execution model.  It allows a program to control multiple different flows of work that overlap in time.  Each flow of work is referred to as a thread, and creation and control over these flows is achieved by making calls to the POSIX Threads API. POSIX Threads is an API defined by the Institute of Electrical and Electronics Engineers (IEEE) standard POSIX.1c, Threads extensions (IEEE Std 1003.1c-1995).
Implementations of the API are available on many Unix-like POSIX-conformant operating systems such as FreeBSD, NetBSD, OpenBSD, Linux, macOS, Android, Solaris, Redox, QNX, and AUTOSAR Adaptive, typically bundled as a library libpthread. DR-DOS and Microsoft Windows implementations also exist: within the SFU/SUA subsystem which provides a native implementation of a number of POSIX APIs, and also within third-party packages such as pthreads-w32, which implements pthreads on top of existing Windows API.

## Related

- [[Micro-thread (multi-core)]]
- [[Multithreading (computer architecture)]]
- [[Native POSIX Thread Library]]
- [[Single instruction, multiple threads]]
- [[Task parallelism]]
- [[Thread pool]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pthreads