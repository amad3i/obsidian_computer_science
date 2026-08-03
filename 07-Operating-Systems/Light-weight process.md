---
title: "Light-weight process"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Light-weight_process"
wikipedia_categories: ["Process (computing)", "Scheduling (computing)"]
related: ["[[Background process]]", "[[Blocking (computing)]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]", "[[Coprocess]]", "[[Daemon (computing)]]"]
---

# Light-weight process

In computer operating systems, a light-weight process (LWP) is a means of achieving multitasking. In the traditional meaning of the term, as used in Unix System V and Solaris, a LWP runs in user space on top of a single kernel thread and shares its address space and system resources with other LWPs within the same process. Multiple user-level threads, managed by a thread library, can be placed on top of one or many LWPs - allowing multitasking to be done at the user level, which can have some performance benefits.
In some operating systems, there is no separate LWP layer between kernel threads and user threads. This means that user threads are implemented directly on top of kernel threads. In those contexts, the term "light-weight process" typically refers to kernel threads and the term "threads" can refer to user threads. On Linux, user threads are implemented by allowing certain processes to share resources, which sometimes leads to these processes to be called "light weight processes". Similarly, in SunOS version 4 onwards (prior to Solaris) "light weight process" referred to user threads.

## Related

- [[Background process]]
- [[Blocking (computing)]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Context switch]]
- [[Coprocess]]
- [[Daemon (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Light-weight_process