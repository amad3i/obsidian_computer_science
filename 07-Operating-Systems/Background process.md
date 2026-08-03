---
title: "Background process"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Background_process"
wikipedia_categories: ["Process (computing)"]
related: ["[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]", "[[Coprocess]]", "[[Daemon (computing)]]", "[[DESQview]]", "[[Divergence (computer science)]]"]
---

# Background process

A background process is a computer process that runs behind the scenes (i.e., in the background) and without user intervention. Typical tasks for these processes include logging, system monitoring, scheduling, and user notification.
On a Windows system, a background process is either a computer program that does not create a user interface, or a Windows service. The former are started just as any other program is started, e.g., via Start menu. Windows services, on the other hand, are started by Service Control Manager. In Windows Vista and later, they are run in a separate session.
On a Unix-like system, a daemon would be a background process. However, in a shell that supports job control, a process that is in a process group whose process group ID differs from its terminal group ID (TGID) would be a background process. (The TGID of a process is the process ID of the process group leader that opened the terminal, which is typically the login shell. The TGID identifies the control terminal of the process group.) This type of process is unable to receive keyboard signals from its parent terminal, and typically will not send output to that terminal. This more technical definition does not distinguish between whether or not the process can receive user intervention. Although background processes are typically used for purposes needing few resources, any process can be run in the background, and such a process will behave like any other process, with the exceptions given above.

## Related

- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Context switch]]
- [[Coprocess]]
- [[Daemon (computing)]]
- [[DESQview]]
- [[Divergence (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Background_process