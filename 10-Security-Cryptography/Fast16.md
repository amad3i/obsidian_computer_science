---
title: "Fast16"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Fast16"
wikipedia_categories: ["2000s in hacking", "Cyberattacks", "Malware", "Malware targeting industrial control systems", "Rootkits"]
related: ["[[Gayfemboy]]", "[[Careto (malware)]]", "[[CovidLock]]", "[[MoonBounce]]", "[[Nitro Zeus]]", "[[Agent Tesla]]", "[[Anti-Malware Testing Standards Organization]]", "[[Backdoor (computing)]]", "[[BadBIOS]]", "[[Blue Frog]]"]
---

# Fast16

Fast16 is a cyber sabotage framework and malware platform. Core components of the framework date back to approximately 2005, making it one of the earliest known examples of precision industrial sabotage, predating the public discovery of the Stuxnet worm by five years. The malware was identified by researchers from SentinelOne, who linked it to the signatures found in the 2017 Shadow Brokers leak of tools allegedly belonging to the National Security Agency.
The framework is characterized by its use of an embedded Lua virtual machine for modularity and a kernel-mode filesystem driver designed for "adversary-in-the-simulation" attacks. Unlike traditional malware designed for data exfiltration or system destruction, Fast16 targets high-precision engineering and simulation software, specifically suites such as LS-DYNA, AUTODYN, PKPM, and MOHID. It utilizes a rule-based engine to intercept executable files in memory and subtly patch floating-point arithmetic routines. These systematic manipulations are intended to produce inaccurate mathematical results in physical modeling, which could lead to inexplicable engineering failures or the sabotage of sensitive research, such as nuclear weapons simulations.

## Related

- [[Gayfemboy]]
- [[Careto (malware)]]
- [[CovidLock]]
- [[MoonBounce]]
- [[Nitro Zeus]]
- [[Agent Tesla]]
- [[Anti-Malware Testing Standards Organization]]
- [[Backdoor (computing)]]
- [[BadBIOS]]
- [[Blue Frog]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fast16