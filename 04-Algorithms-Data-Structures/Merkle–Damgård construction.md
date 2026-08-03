---
title: "Merkle–Damgård construction"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Merkle–Damgård_construction"
wikipedia_categories: ["Cryptographic hash functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypt (C)]]", "[[Cryptographic hash function]]", "[[Elliptic curve only hash]]", "[[Fast syndrome-based hash]]", "[[FORK-256]]"]
---

# Merkle–Damgård construction

In cryptography, the Merkle–Damgård construction or Merkle–Damgård hash function is a method of building collision-resistant cryptographic hash functions from collision-resistant one-way compression functions. This construction was used in the design of many popular hash algorithms such as MD5, SHA-1, and SHA-2.
The Merkle–Damgård construction was described in Ralph Merkle's Ph.D. thesis in 1979. Ralph Merkle and Ivan Damgård independently proved that the structure is sound: that is, if an appropriate padding scheme is used and the compression function is collision-resistant, then the hash function will also be collision-resistant.
The Merkle–Damgård hash function first applies an MD-compliant padding function to create an input whose size is a multiple of a fixed number (e.g. 512 or 1024) — this is because compression functions cannot handle inputs of arbitrary size. The hash function then breaks the result into blocks of fixed size, and processes them one at a time with the compression function, each time combining a block of the input with the output of the previous round. In order to make the construction secure, Merkle and Damgård proposed that messages be padded with a padding that encodes the length of the original message. This is called length padding or Merkle–Damgård strengthening.

In the diagram, the one-way compression function is denoted by f, and transforms two fixed length inputs to an output of the same size as one of the inputs. The algorithm starts with an initial value, the initialization vector (IV). The IV is a fixed value (algorithm- or implementation-specific). For each message block, the compression (or compacting) function f takes the result so far, combines it with the message block, and produces an intermediate result. The last block is padded with zeros as needed and bits representing the length of the entire message are appended. (See below for a detailed length-padding example.)
To harden the hash further, the last result is then sometimes fed through a finalisation function. The finalisation function can have several purposes such as compressing a bigger internal state (the last result) into a smaller output hash size or to guarantee a better mixing and avalanche effect on the bits in the hash sum. The finalisation function is often built by using the compression function. (Note that in some documents a different terminology is used: the act of length padding is called "finalisation".)

## Related

- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypt (C)]]
- [[Cryptographic hash function]]
- [[Elliptic curve only hash]]
- [[Fast syndrome-based hash]]
- [[FORK-256]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Merkle–Damgård_construction