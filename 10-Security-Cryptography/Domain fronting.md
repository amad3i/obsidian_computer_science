---
title: "Domain fronting"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Domain_fronting"
wikipedia_categories: ["Computer security"]
related: ["[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]", "[[Attack path management]]", "[[Automated penetration testing]]", "[[Automotive security]]"]
---

# Domain fronting

Domain fronting is a technique for Internet censorship circumvention that uses different domain names in different communication layers of an HTTPS connection to discreetly connect to a different target domain than that which is discernable to third parties monitoring the requests and connections.
Due to quirks in security certificates, the redirect systems of the content delivery networks (CDNs) used as 'domain fronts', and the protection provided by HTTPS, censors are typically unable to differentiate circumvention ("domain-fronted") traffic from overt non-fronted traffic for any given domain name. As such they are forced to either allow all traffic to the domain front—including circumvention traffic—or block the domain front entirely, which may result in expensive collateral damage and has been likened to "blocking the rest of the Internet".
Domain fronting is achieved by a mismatch of the HTTP Host header and the TLS SNI extension. The standard that defines the SNI extension discourages such a mismatch but does not forbid it. Many large cloud service providers, including Amazon, Microsoft, and Google, actively prohibit domain fronting, which has limited it as a censorship bypass technique. Pressure from censors in Russia and China is thought to have contributed to these prohibitions, but domain fronting can also be used maliciously.
A variant of domain fronting, domain hiding, passes an encrypted request for one resource (say, a website), concealed behind an unencrypted (plaintext) request for another resource whose DNS records are stored in the same cloud. It has much the same effect. As of August 2020, Cloudflare started refusing requests sent with both plaintext and encrypted destinations, rendering the initial implementation of the method only capable of obscuring the destination, but not bypassing firewalls.  Refraction networking is an application of the broader principle.

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

- Wikipedia: https://en.wikipedia.org/wiki/Domain_fronting