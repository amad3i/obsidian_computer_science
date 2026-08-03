---
title: "Linear code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Linear_code"
wikipedia_categories: ["Coding theory", "Finite fields"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[BCH code]]", "[[Berlekamp–Welch algorithm]]", "[[Concatenated error correction code]]", "[[Cyclic code]]", "[[Generalized minimum-distance decoding]]", "[[Homomorphic signatures for network coding]]", "[[Justesen code]]", "[[Linear network coding]]"]
---

# Linear code

In coding theory, a linear code is an error-correcting code for which any linear combination of codewords is also a codeword. Linear codes are traditionally partitioned into block codes and convolutional codes, although turbo codes can be seen as a hybrid of these two types. Linear codes allow for more efficient encoding and decoding algorithms than other codes (cf. syndrome decoding).
Linear codes are used in forward error correction and are applied in methods for transmitting symbols (e.g., bits) on a communications channel so that, if errors occur in the communication, some errors can be corrected or detected by the recipient of a message block.  The codewords in a linear block code are blocks of symbols that are encoded using more symbols than the original value to be sent.  A linear code of length n transmits blocks containing n symbols.  For example, the [7,4,3] Hamming code is a linear binary code which represents 4-bit messages using 7-bit codewords.  Two distinct codewords differ in at least three bits.  As a consequence, up to two errors per codeword can be detected while a single error can be corrected.  This code contains 24 = 16 codewords.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[BCH code]]
- [[Berlekamp–Welch algorithm]]
- [[Concatenated error correction code]]
- [[Cyclic code]]
- [[Generalized minimum-distance decoding]]
- [[Homomorphic signatures for network coding]]
- [[Justesen code]]
- [[Linear network coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linear_code