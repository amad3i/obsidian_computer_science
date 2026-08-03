---
title: "Fork (system call)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Fork_(system_call)"
wikipedia_categories: ["C POSIX library", "Process (computing)", "System calls"]
related: ["[[Wait (system call)]]", "[[Exec (system call)]]", "[[Fork–exec]]", "[[Poll (Unix)]]", "[[Spawn (computing)]]", "[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]"]
---

# Fork (system call)

In computing, fork is an operation whereby a process creates a copy of itself. It is usually implemented as a C standard library wrapper to the fork, clone, or other system calls of the kernel. For many years, fork was the primary method of process creation on Unix and Unix-like operating systems, and it remains a required interface for compliance with POSIX. Despite this, it has fallen out of favor in recent years as a result of flaws including poor performance, a lack of thread safety, and its status as a common source of security vulnerabilities.

## Related

- [[Wait (system call)]]
- [[Exec (system call)]]
- [[Fork–exec]]
- [[Poll (Unix)]]
- [[Spawn (computing)]]
- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fork_(system_call)