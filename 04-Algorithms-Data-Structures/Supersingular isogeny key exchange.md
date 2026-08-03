---
title: "Supersingular isogeny key exchange"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Supersingular_isogeny_key_exchange"
wikipedia_categories: ["Broken cryptographic algorithms", "Cryptographic algorithms", "Post-quantum cryptography"]
related: ["[[Ring learning with errors key exchange]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]", "[[Crypt (C)]]"]
---

# Supersingular isogeny key exchange

Supersingular isogeny Diffie–Hellman key exchange (SIDH or SIKE) was an insecure proposal for a post-quantum cryptographic algorithm to establish a secret key between two parties over an untrusted communications channel. It is analogous to the Diffie–Hellman key exchange, but is based on walks in a supersingular isogeny graph and was designed to resist cryptanalytic attack by an adversary in possession of a quantum computer. Before it was broken, SIDH boasted one of the smallest key sizes of all post-quantum key exchanges; with compression, SIDH used 2688-bit public keys at a 128-bit quantum security level. SIDH also distinguishes itself from similar systems such as NTRU and Ring-LWE  by supporting perfect forward secrecy, a property that prevents compromised long-term keys from compromising the confidentiality of old communication sessions. These properties seemed to make SIDH a natural candidate to replace Diffie–Hellman (DHE) and elliptic curve Diffie–Hellman (ECDHE), which are widely used in Internet communication. However, SIDH is vulnerable to a devastating key-recovery attack published in July 2022 and is therefore insecure. The attack does not require a quantum computer.

## Related

- [[Ring learning with errors key exchange]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]
- [[Crypt (C)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Supersingular_isogeny_key_exchange