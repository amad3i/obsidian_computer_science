---
title: "Code (cryptography)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Code_(cryptography)"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Code (cryptography)

In cryptology, a code is a method used to encrypt a message that operates at the level of meaning; that is, words or phrases are converted into something else. A code might transform "change" into "CVGDK" or "cocktail lounge". The U.S. National Security Agency defined a code as "A substitution cryptosystem in which the plaintext elements are primarily words, phrases, or sentences, and the code equivalents (called "code groups") typically consist of letters or digits (or both) in otherwise meaningless combinations of identical length." A codebook is needed to encrypt, and decrypt the phrases or words.
By contrast, ciphers encrypt messages at the level of individual letters, or small groups of letters, or even, in modern ciphers, individual bits. Messages can be transformed first by a code, and then by a cipher. Such multiple encryption, or "superencryption" aims to make cryptanalysis more difficult.
Another comparison between codes and ciphers is that a code typically represents a letter or groups of letters directly without the use of mathematics. As such the numbers are configured to represent  these three values: 1001 = A, 1002 = B, 1003 = C, ... . The resulting message, then would be 1001 1002 1003 to communicate ABC. Ciphers, however, utilize a mathematical formula to represent letters or groups of letters.  For example, A = 1, B = 2, C = 3, ... . Thus the message ABC results by multiplying each letter's value by 13. The message ABC, then would be 13 26 39.
Codes have a variety of drawbacks, including susceptibility to cryptanalysis and the difficulty of managing the cumbersome codebooks, so ciphers are now the dominant technique in modern cryptography.
In contrast, because codes are representational, they are not susceptible to mathematical analysis of the individual codebook elements. In the example, the message 13 26 39 can be cracked by dividing each number by 13 and then ranking them alphabetically. However, the focus of codebook cryptanalysis is the comparative frequency of the individual code elements matching the same frequency of letters within the plaintext messages using frequency analysis. In the above example, the code group, 1001, 1002, 1003, might occur more than once and that frequency might match the number of times that ABC occurs in plain text messages.
(In the past, or in non-technical contexts, code and cipher are often used to refer to any form of encryption).

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]
- [[Batch cryptography]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Code_(cryptography)