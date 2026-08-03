---
title: "Double Ratchet Algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Double_Ratchet_Algorithm"
wikipedia_categories: ["Cryptographic algorithms", "End-to-end encryption"]
related: ["[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]", "[[CryptGenRandom]]", "[[Crypto++]]"]
---

# Double Ratchet Algorithm

In cryptography, the Double Ratchet Algorithm (previously referred to as the Axolotl Ratchet) is a key management algorithm that was developed by Trevor Perrin and Moxie Marlinspike in 2013. It can be used as part of a cryptographic protocol to provide end-to-end encryption for instant messaging. After an initial key exchange it manages the ongoing renewal and maintenance of short-lived session keys. It combines a cryptographic so-called "ratchet" based on the Diffie–Hellman key exchange (DH) and a ratchet based on a key derivation function (KDF), such as a hash function, and is therefore called a double ratchet.
The algorithm provides forward secrecy for messages, and implicit renegotiation of forward keys; properties for which the protocol is named.
This has been extended as of October 2025 to the Sparse Post Quantum Ratchet (SPQR) with a CRYSTALS-Kyber quantum ratchet to provide post-quantum Forward Secrecy and Post-Compromise Security guarantees in what the Signal authors call a Triple Ratchet.

## Related

- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]
- [[CryptGenRandom]]
- [[Crypto++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Double_Ratchet_Algorithm