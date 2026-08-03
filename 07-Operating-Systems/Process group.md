---
title: "Process group"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Process_group"
wikipedia_categories: ["POSIX", "Process (computing)"]
related: ["[[Exec (system call)]]", "[[Exit (system call)]]", "[[Background process]]", "[[Bourne shell]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]"]
---

# Process group

In a POSIX-conformant operating system, a process group denotes a collection of one or more processes.
Among other things, a process group is used to control the distribution of a signal;
when a signal is directed to a process group, the signal is delivered to each process that is a member of the group.
Similarly, a session denotes a collection of one or more process groups.
A process may not create a process group that belongs to another session;
furthermore, a process is not permitted to join a process group that is a member of another session—that is, a process is not permitted to migrate from one session to another.
When a process replaces its image with a new image (by calling one of the exec functions), the new image is subjected to the same process group (and thus session) membership as the old image.

## Related

- [[Exec (system call)]]
- [[Exit (system call)]]
- [[Background process]]
- [[Bourne shell]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Context switch]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Process_group