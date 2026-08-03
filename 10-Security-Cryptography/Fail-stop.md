---
title: "Fail-stop"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Fail-stop"
wikipedia_categories: ["Computer security", "Software engineering terminology"]
related: ["[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]", "[[Architecture astronaut]]", "[[Attack path management]]", "[[Automated penetration testing]]"]
---

# Fail-stop

A fail-stop subset of a computer language is one that has the same semantics as the original, except in the case where an exceptional condition arises.  The fail-stop subset must report an exceptional condition whenever the superset language reports one, but may additionally report an exceptional condition in other cases.
Fail-stop languages are often used in computer systems where correctness is very important, since it is easier to make such systems fail-fast.  For example, the "+" operator in many programming languages is not associative because of the possibility of floating-point overflow.  Repairing these languages to fail fast when commonly assumed properties do not hold makes it much easier to write and verify correct code.

## Related

- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]
- [[Architecture astronaut]]
- [[Attack path management]]
- [[Automated penetration testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fail-stop