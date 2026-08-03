---
title: "Zombie process"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Zombie_process"
wikipedia_categories: ["Metaphors referring to zombies", "Process (computing)"]
related: ["[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]", "[[Coprocess]]", "[[Daemon (computing)]]", "[[DESQview]]"]
---

# Zombie process

On Unix and Unix-like computer operating systems, a zombie process or defunct process is a process that has completed execution (via the exit system call) but still has an entry in the process table: it is a process in the "terminated state". This occurs for the child processes, where the entry is still needed to allow the parent process to read its child's exit status: once the exit status is read via the  wait system call, the defunct process' entry is removed from the process table and it is said to be "reaped". A child process initially becomes defunct, only then being removed from the resource table. Under normal system operation, defunct processes are immediately waited on by their parent and then reaped by the system. Processes that stay defunct for a long time are usually an error and can cause a resource leak. Generally, the only kernel resource they occupy is the process table entry, their process ID. However, defuncts can also hold buffers open, consuming memory. Defunct processes can hold handles to file descriptors, which prevents the space for those files from being available to the filesystem. This effect can be seen by a difference between du and df. While du may show a large amount of free disk space, df will show a full partition. If the defuncts are not cleaned, this can fill the root partition and crash the system.
The term zombie process derives from the common definition of zombie – an undead person. In the term's metaphor, the child process has "died" but has not yet been "reaped". Unlike normal processes, the kill command has no effect on a zombie process.
Zombie processes should not be confused with orphan processes, a process that is still executing, but whose parent has died. When the parent dies, the orphaned child process is adopted by init. When orphan processes die, they do not remain as zombie processes; instead, they are waited on by init.

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

- Wikipedia: https://en.wikipedia.org/wiki/Zombie_process