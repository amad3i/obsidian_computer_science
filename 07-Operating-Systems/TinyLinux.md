---
title: "TinyLinux"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/TinyLinux"
wikipedia_categories: ["Linux kernel", "Linux stubs"]
related: ["[[Linux Test Project]]", "[[Mm tree]]", "[[SLOB]]", "[[SLUB (software)]]", "[[-dev-full]]", "[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]"]
---

# TinyLinux

TinyLinux is a project started by Matt Mackall in 2003 to reduce the size of the Linux kernel, in both memory usage and binary filesize. The purpose was to make a compact Linux system  for embedded devices. The development was sponsored by the CE Linux Forum. It is also known as the -tiny tree.
By 2006 the project was mostly abandoned. It received new attention in 2007, again with sponsorship from CELF, but has seen minimal activity since 2007.
TinyLinux consists of a set of patches against the Linux kernel which make certain features optional, or add system monitoring and measurement so that further optimization can take place. They are made to be mergeable with the mainline kernel, and many patches have been merged to date.
Features include: the ability to disable ELF core dumps, reduce the number of swap files, use of the SLOB memory allocator, ability to disable BUG(). For measuring and accounting features include: ability for kmalloc/kfree allocations to be monitored through /proc/kmalloc; and measurement of inline usage during kernel compiling. TinyLinux requires Intel 80386 or better to run.

## Related

- [[Linux Test Project]]
- [[Mm tree]]
- [[SLOB]]
- [[SLUB (software)]]
- [[-dev-full]]
- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Configuration Menu Language]]
- [[Copy Fail]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TinyLinux