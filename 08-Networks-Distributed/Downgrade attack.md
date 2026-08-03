---
title: "Downgrade attack"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Downgrade_attack"
wikipedia_categories: ["Backward compatibility", "Computer network security", "Cryptographic attacks", "Transport Layer Security", "Web security exploits"]
related: ["[[Man-in-the-middle attack]]", "[[3-subset meet-in-the-middle attack]]", "[[BREACH]]", "[[POODLE]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-Layer Protocol Negotiation]]"]
---

# Downgrade attack

A downgrade attack, also called a bidding-down attack, or version rollback attack, is a form of cryptographic attack on a computer system or communications protocol that makes it abandon a high-quality mode of operation (e.g. an encrypted connection) in favor of an older, lower-quality mode of operation (e.g. cleartext) that is typically provided for backward compatibility with older systems. An example of such a flaw was found in OpenSSL that allowed the attacker to negotiate the use of a lower version of TLS between the client and server. This is one of the most common types of downgrade attacks. Opportunistic encryption protocols such as STARTTLS are generally vulnerable to downgrade attacks, as they, by design, fall back to unencrypted communication.  Websites which rely on redirects from unencrypted HTTP to encrypted HTTPS can also be vulnerable to downgrade attacks (e.g., sslstrip), as the initial redirect is not protected by encryption.

## Related

- [[Man-in-the-middle attack]]
- [[3-subset meet-in-the-middle attack]]
- [[BREACH]]
- [[POODLE]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-Layer Protocol Negotiation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Downgrade_attack