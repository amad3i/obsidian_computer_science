---
title: "Substitution–permutation network"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Substitution–permutation_network"
wikipedia_categories: ["Block ciphers", "Cryptographic algorithms", "Permutations"]
related: ["[[CDMF]]", "[[Advanced Encryption Standard]]", "[[Ascon (cipher)]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher]]", "[[Block cipher mode of operation]]", "[[Ciphertext stealing]]"]
---

# Substitution–permutation network

In cryptography, an SP-network, or substitution–permutation network (SPN), is a series of linked mathematical operations used in block cipher algorithms such as AES (Rijndael), 3-Way,  Kalyna, Kuznyechik, PRESENT, SAFER, SHARK, and Square.
Such a network takes a block of the plaintext and the key as inputs, and applies several alternating rounds or layers of substitution boxes (S-boxes) and permutation boxes (P-boxes) to produce the ciphertext block. The S-boxes and P-boxes transform (sub-)blocks of input bits into output bits.  It is common for these transformations to be operations that are efficient to perform in hardware, such as exclusive or (XOR) and bitwise rotation. The key is introduced in each round, usually in the form of "round keys" derived from it. (In some designs, the S-boxes themselves depend on the key.)
Decryption is done by simply reversing the process (using the inverses of the S-boxes and P-boxes and applying the round keys in reversed order).

## Related

- [[CDMF]]
- [[Advanced Encryption Standard]]
- [[Ascon (cipher)]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher]]
- [[Block cipher mode of operation]]
- [[Ciphertext stealing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Substitution–permutation_network