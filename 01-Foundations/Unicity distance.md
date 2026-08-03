---
title: "Unicity distance"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Unicity_distance"
wikipedia_categories: ["Cryptographic attacks", "Information theory"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bandwidth (computing)]]", "[[Bandwidth extension]]"]
---

# Unicity distance

In cryptography, unicity distance is the length of an original ciphertext needed to break the cipher by reducing the number of possible spurious keys to zero in a brute force attack. That is, after trying every possible key, there should be just one decipherment that makes sense, i.e. expected amount of ciphertext needed to determine the key completely, assuming the underlying message has redundancy.
Claude Shannon defined the unicity distance in his 1949 paper "Communication Theory of Secrecy Systems".
Consider an attack on the ciphertext string "WNAIW" encrypted using a Vigenère cipher with a five letter key. Conceivably, this string could be deciphered into any other string—RIVER and WATER are both possibilities for certain keys. This is a general rule of cryptanalysis: with no additional information it is impossible to decode this message.
Of course, even in this case, only a certain number of five letter keys will result in English words. Trying all possible keys we will not only get RIVER and WATER, but SXOOS and KHDOP as well. The number of "working" keys will likely be very much smaller than the set of all possible keys. The problem is knowing which of these "working" keys is the right one; the rest are spurious.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bandwidth (computing)]]
- [[Bandwidth extension]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unicity_distance