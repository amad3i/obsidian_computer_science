---
title: "Zigzag code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Zigzag_code"
wikipedia_categories: ["Coding theory", "Error detection and correction", "Telecommunications stubs"]
related: ["[[Alternant code]]", "[[BCH code]]", "[[Berger code]]", "[[Berlekamp–Welch algorithm]]", "[[Burst error-correcting code]]", "[[Coding gain]]", "[[Coding theory]]", "[[Concatenated error correction code]]", "[[Coset leader]]", "[[Delsarte–Goethals code]]"]
---

# Zigzag code

In coding theory, a zigzag code is a type of linear error-correcting code introduced by Ping, Huang & Phamdo (2001). They are defined by partitioning the input data into segments of fixed size, and adding sequence of check bits to the data, where each check bit is the exclusive or of the bits in a single segment and of the previous check bit in the sequence.
The code rate is high: J/(J + 1) where J is the number of bits per segment. Its worst-case ability to correct transmission errors is very limited: in the worst case it can only detect a single bit error and cannot correct any errors. However, it works better in the soft-decision model of decoding: its regular structure allows the task of finding a maximum-likelihood decoding or a posteriori probability decoding to be performed in constant time per input bit.

## Related

- [[Alternant code]]
- [[BCH code]]
- [[Berger code]]
- [[Berlekamp–Welch algorithm]]
- [[Burst error-correcting code]]
- [[Coding gain]]
- [[Coding theory]]
- [[Concatenated error correction code]]
- [[Coset leader]]
- [[Delsarte–Goethals code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Zigzag_code