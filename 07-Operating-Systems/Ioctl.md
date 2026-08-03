---
title: "Ioctl"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Ioctl"
wikipedia_categories: ["System calls", "Unix"]
related: ["[[Poll (Unix)]]", "[[Ptrace]]", "[[Sysctl]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Exec (system call)]]", "[[Fork (system call)]]", "[[FreeBSD jail]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]"]
---

# Ioctl

In computing, ioctl (an abbreviation of input/output control) is a system call for device-specific input/output operations and other operations which cannot be expressed by read/write/seek regular file semantics. It takes a parameter specifying a request code; the effect of a call depends completely on the request code. Request codes are often device-specific. For instance, a CD-ROM device driver which can instruct a physical device to eject a disc would provide an ioctl request code to do so. Device-independent request codes are sometimes used to give userspace access to kernel functions which are only used by core system software or still under development.
The ioctl system call first appeared in Version 7 of Unix under that name. It is supported by most Unix and Unix-like systems, including Linux and macOS, though the available request codes differ from system to system. Microsoft Windows provides a similar function, named "DeviceIoControl", in its Win32 API.

## Related

- [[Poll (Unix)]]
- [[Ptrace]]
- [[Sysctl]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Exec (system call)]]
- [[Fork (system call)]]
- [[FreeBSD jail]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ioctl