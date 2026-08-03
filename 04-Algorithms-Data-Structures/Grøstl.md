---
title: "Grøstl"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Grøstl"
wikipedia_categories: ["Cryptographic hash functions", "Cryptography stubs", "NIST hash function competition"]
related: ["[[JH (hash function)]]", "[[Ascon (cipher)]]", "[[FORK-256]]", "[[Gimli (cipher)]]", "[[HAIFA construction]]", "[[HAS-160]]", "[[HAS-V]]", "[[HAVAL]]", "[[MD6]]", "[[N-hash]]"]
---

# Grøstl

Grøstl is a cryptographic hash function submitted to the NIST hash function competition by Praveen Gauravaram, Lars Knudsen, Krystian Matusiewicz, Florian Mendel, Christian Rechberger, Martin Schläffer, and Søren S. Thomsen. Grøstl was chosen as one of the five finalists of the competition. It uses the same S-box as AES in a custom construction.  The authors claim speeds of up to 21.4 cycles per byte on an Intel Core 2 Duo, and 9.6 cycles/byte on an Intel i7 with AES-NI.
According to the submission document, the name "Grøstl" is a multilingual play-on-words, referring to an Austrian dish that is very similar to hash (food).
Like other hash functions in the MD5/SHA family, Grøstl divides the input into blocks and iteratively computes hi = f(hi−1, mi).  However, Grøstl maintains a hash state at least twice the size of the final output (512 or 1024 bits), which is only truncated at the end of hash computation.
The compression function f is based on a pair of 512- or 1024-bit permutation functions P and Q, and is defined as:

f(h, m) = P(h ⊕ m) ⊕ Q(m) ⊕ h
The permutation functions P and Q are heavily based on the Rijndael (AES) block cipher, but operate on 8×8 or 8×16 arrays of bytes, rather than 4×4.  Like AES, each round consists of four operations:

AddRoundKey (the Grøstl round keys are fixed, but differ between P and Q)
SubBytes (this uses the Rijndael S-box, allowing sharing with AES implementations)
ShiftBytes (expanded compared to AES, this also differs between P and Q, and 512- and 1024-bit versions)
MixColumns (using an 8×8 matrix rather than Rijndael's 4×4)
Unlike Rijndael, all rounds are identical and there is no final AddRoundKey operation.  10 rounds are recommended for the 512-bit permutation, and 14 rounds for the 1024-bit version.
The final double-width hash receives a final output transformation of

Ω(h) = h ⊕ P(h)
and is then truncated to the desired width.  This is equivalent to applying a final iteration of the compression function using an all-zero message block m, followed by a (cryptographically insignificant) exclusive-or with the fixed constant Q(0).

## Related

- [[JH (hash function)]]
- [[Ascon (cipher)]]
- [[FORK-256]]
- [[Gimli (cipher)]]
- [[HAIFA construction]]
- [[HAS-160]]
- [[HAS-V]]
- [[HAVAL]]
- [[MD6]]
- [[N-hash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Grøstl