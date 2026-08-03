---
title: "Runlevel"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Runlevel"
wikipedia_categories: ["Unix", "Unix process- and task-management-related software"]
related: ["[[Sysctl]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Kill (command)]]", "[[Ldconfig]]", "[[Line discipline]]"]
---

# Runlevel

A runlevel is a mode of operation in the computer operating systems that implements Unix System V-style initialization. Conventionally, seven runlevels exist, numbered from zero to six. S is sometimes used as a synonym for one of the levels. Only one runlevel is executed on startup; run levels are not executed one after another (i.e. only runlevel 2, 3, or 4 is executed, not more of them sequentially or in any other order).
A runlevel defines the state of the machine after boot. Different runlevels are typically assigned (not necessarily in any particular order) to the single-user mode, multi-user mode without network services started, multi-user mode with network services started, system shutdown, and system reboot system states. The exact setup of these configurations varies between operating systems and Linux distributions. For example, runlevel 4 might be a multi-user GUI no-server configuration on one distribution, and nothing on another. Runlevels commonly follow the general patterns described in this article; however, some distributions employ certain specific configurations.
In standard practice, when a computer enters runlevel zero, it shuts off, and when it enters runlevel six, it reboots. The intermediate runlevels (1–5) differ in terms of which drives are mounted and which network services are started. Default runlevels are typically 3, 4, or 5. Lower runlevels are useful for maintenance or emergency repairs, since they usually offer no network services at all. The particular details of runlevel configuration differ widely among operating systems, and also among system administrators.
In various Linux distributions, the traditional /etc/rc script used in the Version 7 Unix was first replaced by runlevels and then by systemd states on most major distributions.

## Related

- [[Sysctl]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Kill (command)]]
- [[Ldconfig]]
- [[Line discipline]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Runlevel