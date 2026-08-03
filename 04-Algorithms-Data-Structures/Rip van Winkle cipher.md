---
title: "Rip van Winkle cipher"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Rip_van_Winkle_cipher"
wikipedia_categories: ["Cryptographic algorithms", "Cryptography stubs"]
related: ["[[CDMF]]", "[[MOSQUITO]]", "[[PEGASUS]]", "[[Alternant code]]", "[[Ascon (cipher)]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[Batch cryptography]]", "[[BB84]]", "[[Beaufort cipher]]"]
---

# Rip van Winkle cipher

In cryptography, the Rip van Winkle cipher is a provably secure cipher with a finite key, assuming the attacker has only finite storage.
The cipher requires a broadcaster (perhaps a numbers station) publicly transmitting a series of random numbers.
The sender encrypts a plaintext message by XORing it with the random numbers, then holding it some length of time T.
At the end of that time, the sender finally transmits the encrypted message.
The receiver holds the random numbers the same length of time T.
As soon as the receiver gets the encrypted message, he XORs it with the random numbers he remembers were transmitted T ago, to recover the original plaintext message.
The delay T represents the "key" and must be securely communicated only once.

Ueli Maurer says the original Rip van Winkle cipher is completely impractical, but it motivated a new approach to provable security.

## Related

- [[CDMF]]
- [[MOSQUITO]]
- [[PEGASUS]]
- [[Alternant code]]
- [[Ascon (cipher)]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[Batch cryptography]]
- [[BB84]]
- [[Beaufort cipher]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rip_van_Winkle_cipher