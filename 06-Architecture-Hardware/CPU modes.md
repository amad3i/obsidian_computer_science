---
title: "CPU modes"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/CPU_modes"
wikipedia_categories: ["Central processing unit", "Computer security"]
related: ["[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]", "[[Arithmetic logic unit]]", "[[Attack path management]]", "[[Automated penetration testing]]"]
---

# CPU modes

CPU modes (also called processor modes, CPU states, CPU privilege levels and other names) are operating modes for the central processing unit of most computer architectures that place restrictions on the type and scope of operations that can be performed by instructions being executed by the CPU. For example, this design allows an operating system to run with more privileges than application software by running the operating systems and applications in different modes.
Ideally, only highly trusted kernel code is allowed to execute in the unrestricted mode; everything else (including non-supervisory portions of the operating system) runs in a restricted mode and must use a system call (via interrupt) to request the kernel perform on its behalf any operation that could damage or compromise the system, making it impossible for untrusted programs to alter or damage other programs (or the computing system itself). Device drivers are designed to be part of the kernel due to the need for frequent I/O access.
Multiple modes can be implemented, e.g. allowing a hypervisor to run multiple operating system supervisors beneath it, which is the basic design of many virtual machine systems available today.

## Related

- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]
- [[Arithmetic logic unit]]
- [[Attack path management]]
- [[Automated penetration testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CPU_modes