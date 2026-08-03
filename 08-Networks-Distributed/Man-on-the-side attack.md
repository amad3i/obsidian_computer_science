---
title: "Man-on-the-side attack"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Man-on-the-side_attack"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Man-on-the-side attack

A man-on-the-side attack is a form of active attack in computer security  similar to a man-in-the-middle attack. Instead of completely controlling a network node as in a man-in-the-middle attack, the attacker only has regular access to the communication channel, which allows them to read the traffic and insert new messages, but not to modify or delete messages sent by other participants. The attacker relies on a timing advantage to make sure that the response they send to the request of a victim arrives before the legitimate response.
In real-world attacks, the response packet sent by the attacker can be used to place malware on the victim's computer. The need for a timing advantage makes the attack difficult to execute, as it requires a privileged position in the network, for example on the internet backbone. Potentially, this class of attack may be performed within a local network (assuming a privileged position), research has shown that it has been successful within critical infrastructure.
The 2013 global surveillance revelations revealed that the US National Security Agency (NSA) widely uses a man-on-the-side attack to infect targets with malware through its QUANTUM program.
GitHub suffered such an attack in 2015. The Russian Threat Group might have suffered a similar attack in 2019.

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
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Man-on-the-side_attack