---
title: "Homomorphic signatures for network coding"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Homomorphic_signatures_for_network_coding"
wikipedia_categories: ["Coding theory", "Error detection and correction", "Finite fields", "Information theory"]
related: ["[[Generalized minimum-distance decoding]]", "[[Zyablov bound]]", "[[Alternant code]]", "[[BCH code]]", "[[Berlekamp–Welch algorithm]]", "[[Concatenated error correction code]]", "[[Justesen code]]", "[[Linear network coding]]", "[[Preparata code]]", "[[Srivastava code]]"]
---

# Homomorphic signatures for network coding

Network coding has been shown to optimally use bandwidth in a network, maximizing information flow but the scheme is very inherently vulnerable to pollution attacks by malicious nodes in the network. A node injecting garbage can quickly affect many receivers.  The pollution of network packets spreads quickly since the output of (even an) honest node is corrupted if at least one of the incoming packets is corrupted.
An attacker can easily corrupt a packet even if it is encrypted by either forging the signature or by producing a collision under the hash function. This will give an attacker access to the packets and the ability to corrupt them. Denis Charles, Kamal Jain and Kristin Lauter designed a new homomorphic encryption signature scheme for use with network coding to prevent pollution attacks.
The homomorphic property of the signatures allows nodes to sign any linear combination of the incoming packets without contacting the signing authority. In this scheme it is computationally infeasible for a node to sign a linear combination of the packets without disclosing what linear combination was used in the generation of the packet. Furthermore, we can prove that the signature scheme is secure under well known cryptographic assumptions of the hardness of the discrete logarithm problem and the computational Elliptic curve Diffie–Hellman.

## Related

- [[Generalized minimum-distance decoding]]
- [[Zyablov bound]]
- [[Alternant code]]
- [[BCH code]]
- [[Berlekamp–Welch algorithm]]
- [[Concatenated error correction code]]
- [[Justesen code]]
- [[Linear network coding]]
- [[Preparata code]]
- [[Srivastava code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Homomorphic_signatures_for_network_coding