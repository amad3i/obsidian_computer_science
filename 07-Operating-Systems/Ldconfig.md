---
title: "Ldconfig"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Ldconfig"
wikipedia_categories: ["Unix"]
related: ["[[ACM SIGOPS Annual Technical Conference]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Line discipline]]", "[[Line Printer Daemon protocol]]", "[[List of input methods for Unix platforms]]", "[[List of Unix daemons]]"]
---

# Ldconfig

In computing, ldconfig is a shell command used for creating and updating symbolic links and the cache for shared libraries. It is found in most Linux distributions and FreeBSD, and it is part of the glibc package. ldconfig works by searching for .so files in directories specified in the /etc/ld.so.conf file, the trusted directories (/lib and /usr/lib, or /lib64 and /usr/lib64 on multilib systems), and any directories specified on the command line.
The generated binary cache file, /etc/ld.so.cache, is used by ld.so to speed up library lookup at runtime.
ldconfig can be compared to regsvr32 in Windows and ReactOS, and to dyld in macOS.

## Related

- [[ACM SIGOPS Annual Technical Conference]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Line discipline]]
- [[Line Printer Daemon protocol]]
- [[List of input methods for Unix platforms]]
- [[List of Unix daemons]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ldconfig