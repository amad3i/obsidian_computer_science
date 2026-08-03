---
title: "Dirty COW"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Dirty_COW"
wikipedia_categories: ["2016 in computing", "Computer security exploits", "Internet security", "Linux kernel", "Privilege escalation exploits", "Software bugs"]
related: ["[[Buffer overflow]]", "[[Copy Fail]]", "[[Open Threat Exchange]]", "[[POODLE]]", "[[Race condition]]", "[[Racetrack problem]]", "[[2014 celebrity nude photo leak]]", "[[Armitage (computing)]]", "[[Automatic Certificate Management Environment]]", "[[BogoMips]]"]
---

# Dirty COW

Dirty COW (Dirty copy-on-write) is a computer security vulnerability of the Linux kernel that affected all Linux-based operating systems, including Android devices, that used older versions of the Linux kernel created before 2018. It is a local privilege escalation bug that exploits a race condition in the implementation of the copy-on-write mechanism in the kernel's memory-management subsystem. Computers and devices that still use the older kernels remain vulnerable.
The original exploit sample leveraging this vulnerability was discovered by Phil Oester during the investigation of a compromised machine. The author of this sample is still unknown.
Because of the race condition, with the right timing, a local attacker can exploit the copy-on-write mechanism to turn a read-only mapping of a file into a writable mapping. Although it is a local privilege escalation, remote attackers can use it in conjunction with other exploits that allow remote execution of non-privileged code to achieve remote root access on a computer. The attack itself does not leave traces in the system log.
The vulnerability has the Common Vulnerabilities and Exposures designation CVE-2016-5195. Dirty Cow was one of the first security issues transparently fixed in Ubuntu by the Canonical Live Patch service.
It has been demonstrated that the vulnerability can be utilized to root any Android device before Android 7 (Nougat).

## Related

- [[Buffer overflow]]
- [[Copy Fail]]
- [[Open Threat Exchange]]
- [[POODLE]]
- [[Race condition]]
- [[Racetrack problem]]
- [[2014 celebrity nude photo leak]]
- [[Armitage (computing)]]
- [[Automatic Certificate Management Environment]]
- [[BogoMips]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dirty_COW