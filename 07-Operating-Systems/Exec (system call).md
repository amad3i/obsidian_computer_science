---
title: "Exec (system call)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Exec_(system_call)"
wikipedia_categories: ["POSIX", "Process.h", "Process (computing)", "System calls", "Unix SUS2008 utilities"]
related: ["[[Bourne shell]]", "[[Exit (system call)]]", "[[Fork (system call)]]", "[[Kill (command)]]", "[[Process group]]", "[[Spawn (computing)]]", "[[Wait (system call)]]", "[[AWK]]", "[[Background process]]", "[[Chain loading]]"]
---

# Exec (system call)

In computing, exec is a functionality of an operating system that runs an executable file in the context of an already existing process, replacing the previous executable. This act is also referred to as an overlay. It is especially important in Unix-like systems, although it also exists elsewhere. As no new process is created, the process identifier (PID) does not change, but the machine code, data, heap, and stack of the process are replaced by those of the new program.
The exec() call or some variant is available for many programming languages including compiled languages and some scripting languages. In command interpreters, the exec built-in command replaces the shell process with the specified program.

## Related

- [[Bourne shell]]
- [[Exit (system call)]]
- [[Fork (system call)]]
- [[Kill (command)]]
- [[Process group]]
- [[Spawn (computing)]]
- [[Wait (system call)]]
- [[AWK]]
- [[Background process]]
- [[Chain loading]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Exec_(system_call)