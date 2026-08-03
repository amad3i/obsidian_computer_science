---
title: "Honeytoken"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Honeytoken"
wikipedia_categories: ["Computer network security", "Computer security stubs"]
related: ["[[Banner grabbing]]", "[[Cyber range]]", "[[Firewalk (computing)]]", "[[Operation Cyber Condition Zebra]]", "[[Safe@Office]]", "[[VPNBook]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]"]
---

# Honeytoken

Honeytokens are fictitious words or records that are added to legitimate databases. They allow administrators to track data in situations they wouldn't normally be able to track, such as cloud-based networks. If data is stolen, honeytokens allow administrators to identify who it was stolen from or how it was leaked. If, for example, there are three locations for medical records, different honeytokens in the form of fake medical records could be added to each location. Different honeytokens would be in each set of records.
The uniqueness of honeytokens enables their use in an intrusion-detection system (IDS) as it searches for suspicious activity on a computer network, alerting the system administrator to things that would otherwise go unnoticed. While firewalls can only catch threats that have not yet entered a network, honeytokens can mark threats that slipped past a firewall. Honeytokens can be read by a reactive security mechanism to intercept malicious activity, e.g. by dropping packets at the router if they contain the honeytoken. However, such mechanisms have pitfalls; for example, if a honeytoken is poorly chosen so that it appears by chance in legitimate network traffic, those packets will be dropped too.
In the field of computer security, honeytokens are honeypots that are not computer systems. Their value lies not in their use, but in their abuse.  As such, they are a generalization of such ideas as the honeypot and the canary values often used in stack protection schemes. Honeytokens do not necessarily prevent tampering with the data, but instead give the administrator a further measure of confidence in the data integrity.
The term was coined by Augusto Paes de Barros Friday, February 21st, 2003 via a message chain on Seclists.org.

## Related

- [[Banner grabbing]]
- [[Cyber range]]
- [[Firewalk (computing)]]
- [[Operation Cyber Condition Zebra]]
- [[Safe@Office]]
- [[VPNBook]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Honeytoken