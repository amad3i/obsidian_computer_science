---
title: "Confused deputy problem"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Confused_deputy_problem"
wikipedia_categories: ["Computer security", "Privilege escalation exploits"]
related: ["[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]", "[[Attack path management]]", "[[Automated penetration testing]]", "[[Automotive security]]"]
---

# Confused deputy problem

In information security, a confused deputy is a computer program that is tricked by another program (with fewer privileges or less rights) into misusing its authority on the system. It is a specific type of privilege escalation. The confused deputy problem is often cited as an example of why capability-based security is important.
Capability systems protect against the confused deputy problem, whereas access-control list–based systems do not.
Such systems can mitigate the confused deputy problem by eliminating ambient authority, allowing programs to act only on resources for which they hold explicit capabilities, whereas access-control list–based systems are more susceptible to it. However, this protection depends on correct implementation; in formally verified capability systems such as seL4, it can be shown that the kernel enforces capability constraints correctly, preventing such behavior at the system level.

## Related

- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]
- [[Attack path management]]
- [[Automated penetration testing]]
- [[Automotive security]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Confused_deputy_problem