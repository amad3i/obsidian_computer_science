---
title: "Sorcerer's Apprentice syndrome"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Sorcerer's_Apprentice_syndrome"
wikipedia_categories: ["Internet architecture", "Network protocols", "Software bugs"]
related: ["[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Internet Protocol Options]]", "[[Turn restriction routing]]", "[[Xcast]]", "[[6bone]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]"]
---

# Sorcerer's Apprentice syndrome

Sorcerer's Apprentice syndrome (SAS) is a network protocol flaw in the original versions of TFTP. It was named after Goethe's 1797 poem "Der Zauberlehrling" (popularized in the US by the "Sorcerer's Apprentice" segment of the 1940 animated film Fantasia), because the details of its operation closely resemble the disaster that befalls the sorcerer's apprentice: the problem resulted in an ever-growing replication of every packet in the transfer.
The problem occurred because of a known failure mode of the internetwork which, through a mistake on the part of the TFTP protocol designers, was not taken into account when the protocol was designed; the failure mode interacted with several details of the mechanisms of TFTP to produce SAS.

## Related

- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Internet Protocol Options]]
- [[Turn restriction routing]]
- [[Xcast]]
- [[6bone]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sorcerer's_Apprentice_syndrome