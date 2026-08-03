---
title: "Man-in-the-middle attack"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Man-in-the-middle_attack"
wikipedia_categories: ["Computer network security", "Cryptographic attacks", "Transport Layer Security"]
related: ["[[Downgrade attack]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-Layer Protocol Negotiation]]", "[[Application-level gateway]]", "[[Attack tree]]"]
---

# Man-in-the-middle attack

In cryptography and computer security, a man-in-the-middle (MITM) attack, or on-path attack, is a cyberattack where the attacker secretly relays and possibly alters the communications between two parties who believe that they are directly communicating with each other, where in actuality the attacker has inserted themselves between the two user parties.
One example of a MITM attack is active eavesdropping, in which the attacker makes independent connections with the victims and relays messages between them to make them believe they are talking directly to each other over a private connection, when in fact the entire conversation is controlled by the attacker. In this scenario, the attacker must be able to intercept all relevant messages passing between the two victims and inject new ones. This is straightforward in many circumstances; for example, an attacker within range of a Wi-Fi access point hosting a network without encryption could insert themselves as a man in the middle.
As it aims to circumvent mutual authentication, a MITM attack can succeed only when the attacker impersonates each endpoint sufficiently well to satisfy their expectations. Most cryptographic protocols include some form of endpoint authentication specifically to prevent MITM attacks. For example, TLS can authenticate one or both parties using a mutually trusted certificate authority.

## Related

- [[Downgrade attack]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-Layer Protocol Negotiation]]
- [[Application-level gateway]]
- [[Attack tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Man-in-the-middle_attack