---
title: "Wait (system call)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Wait_(system_call)"
wikipedia_categories: ["C POSIX library", "Process (computing)", "System calls"]
related: ["[[Fork (system call)]]", "[[Exec (system call)]]", "[[Fork–exec]]", "[[Poll (Unix)]]", "[[Spawn (computing)]]", "[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]"]
---

# Wait (system call)

In computer operating systems, a process (or task) may wait for another process to complete its execution. In most systems, a parent process can create an independently executing child process. The parent process may then issue a wait system call, which suspends the execution of the parent process while the child executes. When the child process terminates, it returns an exit status to the operating system, which is then returned to the waiting parent process. The parent process then resumes execution.
Modern operating systems also provide system calls that allow a process's thread to create other threads and wait for them to terminate ("join" them) in a similar fashion.
An operating system may provide variations of the wait call that allow a process to wait for any of its child processes to exit, or to wait for a single specific child process (identified by its process ID) to exit.
Some operating systems issue a signal (SIGCHLD) to the parent process when a child process terminates, notifying the parent process and allowing it to retrieve the child process's exit status.
The exit status returned by a child process typically indicates whether the process terminated normally or abnormally. For normal termination, this status also includes the exit code (usually an integer value) that the process returned to the system. During the first 20 years of UNIX, only the low 8 bits of the exit code were available to the waiting parent. In 1989 with SVR4, a new call waitid was introduced that returns all bits from the exit call in a structure called siginfo_t in the structure member si_status. Waitid has been a mandatory part of the POSIX standard since 2001.

## Related

- [[Fork (system call)]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Wait_(system_call)