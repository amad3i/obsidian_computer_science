---
title: "Spl (Unix)"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Spl_(Unix)"
wikipedia_categories: ["Interrupts", "Unix", "Unix stubs"]
related: ["[[Line discipline]]", "[[Message of the day]]", "[[Qsub]]", "[[Symlink race]]", "[[Utmp]]", "[[Words (Unix)]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Busdma]]", "[[Gecos field]]", "[[Group identifier]]"]
---

# Spl (Unix)

spl (short for set priority level, after the PDP-11 assembler instruction of the same name) is the name for a collection of Unix kernel routines or macros used to change the interrupt priority level. This was historically needed to synchronize critical sections of kernel code that should not be interrupted. Newer Unix variants which support symmetric multiprocessing now mostly use mutexes for this purpose, which is a more general solution, so multiple processors can execute kernel code at the same time.
On older PDP-11 versions of Unix, there were eight of these routines, ranging from spl0 to spl7, each corresponding to one PDP-11 interrupt priority level, in addition to splx, which restores a previous priority level (returned by one of the other routines). On BSD Unix and its derivatives, these are called splhigh, splserial, splsched, splclock, splstatclock, splvm, spltty, splsofttty, splnet, splbio, splsoftnet, splsoftclock, spllowersoftclock, spl0, and splx.
As of March 2019, the spl family of primitives is still heavily used in OpenBSD and NetBSD, which is evidenced by the plentiful calls to splnet() within the networking code; whereas FreeBSD and DragonFly BSD use more modern concepts; for example, in DragonFly, LWKT tokens may be used in place of spl.

## Related

- [[Line discipline]]
- [[Message of the day]]
- [[Qsub]]
- [[Symlink race]]
- [[Utmp]]
- [[Words (Unix)]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Busdma]]
- [[Gecos field]]
- [[Group identifier]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spl_(Unix)