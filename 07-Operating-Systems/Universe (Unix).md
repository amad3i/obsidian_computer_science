---
title: "Universe (Unix)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Universe_(Unix)"
wikipedia_categories: ["Unix"]
related: ["[[ACM SIGOPS Annual Technical Conference]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Ldconfig]]", "[[Line discipline]]", "[[Line Printer Daemon protocol]]", "[[List of input methods for Unix platforms]]"]
---

# Universe (Unix)

In some versions of the Unix operating system, the term universe was used to denote some variant of the working environment. During the late 1980s, most commercial Unix variants were derived from either System V or BSD. Some versions provided both BSD and System V universes and allowed the user to switch between them. Each universe, typically implemented by separate directory trees or separate filesystems, usually included different versions of commands, libraries, man pages, and header files. While such a facility offered the ability to develop applications portable across both System V and BSD variants, the requirements in disk space and maintenance (separate configuration files, twice the work in patching systems) gave them a problematic reputation.
Systems that offered this facility included Control Data Corporation's EP/IX, Harris/Concurrent's CX/UX, Convex's ConvexOS, Apollo's Domain/OS (version 10 only), Pyramid's DC/OSx (dropped in SVR4-based version 2), Concurrent/MASSCOMP's Masscomp/RTU, MIPS Computer Systems' RISC/os, Sequent's DYNIX and Siemens' SINIX.
Some versions of System V Release 4 (such as Solaris) retain a system similar to the universe concept, with BSD commands (which behave differently from classic System V commands) in /usr/ucb, BSD header files in /usr/ucbinclude and library files in /usr/ucblib. /usr/ucb can also be found in NeXTSTEP and OPENSTEP.

## Related

- [[ACM SIGOPS Annual Technical Conference]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Ldconfig]]
- [[Line discipline]]
- [[Line Printer Daemon protocol]]
- [[List of input methods for Unix platforms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Universe_(Unix)