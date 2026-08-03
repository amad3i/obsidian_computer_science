---
title: "Verifiable random function"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Verifiable_random_function"
wikipedia_categories: ["Cryptographic algorithms", "Cryptographic primitives", "Pseudorandomness"]
related: ["[[Cryptographically secure pseudorandom number generator]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]"]
---

# Verifiable random function

In cryptography, a verifiable random function (VRF) is a public-key pseudorandom function that provides proofs that its outputs were calculated correctly. The owner of the secret key can compute the function value as well as an associated proof for any input value. Everyone else, using the proof and the associated public key (or verification key), can check that this value was indeed calculated correctly, yet this information cannot be used to find the secret key.
A verifiable random function can be viewed as a public-key analogue of a keyed cryptographic hash and as a cryptographic commitment to an exponentially large number of seemingly random bits. The concept of a verifiable random function is closely related to that of a verifiable unpredictable function (VUF), whose outputs are hard to predict but do not necessarily seem random.
The concept of a VRF was introduced by Micali, Rabin, and Vadhan in 1999. Since then, verifiable random functions have found widespread use in cryptocurrencies, as well as in proposals for protocol design and cybersecurity.

## Related

- [[Cryptographically secure pseudorandom number generator]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Verifiable_random_function