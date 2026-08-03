---
title: "Supervisor Mode Access Prevention"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Supervisor_Mode_Access_Prevention"
wikipedia_categories: ["Computer security", "Intel", "X86 instructions", "X86 memory management"]
related: ["[[Intel Management Engine]]", "[[Intel Threat Detection Technology]]", "[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Advanced Synchronization Facility]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]"]
---

# Supervisor Mode Access Prevention

Supervisor Mode Access Prevention (SMAP) is a feature of some CPU implementations such as the Intel Broadwell microarchitecture that allows supervisor mode programs to optionally set user-space memory mappings so that access to those mappings from supervisor mode will cause a trap. This makes it harder for malicious programs to "trick" the kernel into using instructions or data from a user-space program.

## Related

- [[Intel Management Engine]]
- [[Intel Threat Detection Technology]]
- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Advanced Synchronization Facility]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Supervisor_Mode_Access_Prevention