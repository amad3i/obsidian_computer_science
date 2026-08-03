---
title: "Exit status"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Exit_status"
wikipedia_categories: ["Process (computing)"]
related: ["[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]", "[[Coprocess]]", "[[Daemon (computing)]]", "[[DESQview]]"]
---

# Exit status

In computing, the exit status (also exit code or exit value) of a terminated process is an integer number that is made available to its parent process (or caller).  In DOS, this may be referred to as an errorlevel.
When computer programs are executed, the operating system creates an abstract entity called a process in which the book-keeping for that program is maintained. In multitasking operating systems such as Unix or Linux, new processes can be created by active processes. The process that spawns another is called a parent process, while those created are child processes.  Child processes run concurrently with the parent process. The technique of spawning child processes is used to delegate some work to a child process when there is no reason to stop the execution of the parent.  When the child finishes executing, it exits by calling the exit system call.  This system call facilitates passing the exit status code back to the parent, which can retrieve this value using the wait system call.

## Related

- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Context switch]]
- [[Coprocess]]
- [[Daemon (computing)]]
- [[DESQview]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Exit_status