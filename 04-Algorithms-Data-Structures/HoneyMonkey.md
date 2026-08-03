---
title: "HoneyMonkey"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/HoneyMonkey"
wikipedia_categories: ["Computer network security", "Microsoft Research"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[AWM–Microsoft Research Prize in Algebra and Number Theory]]"]
---

# HoneyMonkey

HoneyMonkey, short for Strider HoneyMonkey Exploit Detection System, is a Microsoft Research honeypot. The implementation uses a network of computers to crawl the World Wide Web searching for websites that use browser exploits to install malware on the HoneyMonkey computer. A snapshot of the memory, executables and registry of the honeypot computer is recorded before crawling a site. After visiting the site, the state of memory, executables, and registry is recorded and compared to the previous snapshot. The changes are analyzed to determine if the visited site installed any malware onto the client honeypot computer.
HoneyMonkey is based on the honeypot concept, with the difference that it actively seeks websites that try to exploit it. The term was coined by Microsoft Research in 2005. With honeymonkeys it is possible to find open security holes that are not yet publicly known but are being exploited by attackers.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[AWM–Microsoft Research Prize in Algebra and Number Theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HoneyMonkey