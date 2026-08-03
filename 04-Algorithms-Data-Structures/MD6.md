---
title: "MD6"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/MD6"
wikipedia_categories: ["Cryptographic hash functions", "NIST hash function competition"]
related: ["[[Grøstl]]", "[[JH (hash function)]]", "[[NIST hash function competition]]", "[[SANDstorm hash]]", "[[SHA-3]]", "[[Skein (hash function)]]", "[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Collision attack]]"]
---

# MD6

The MD6 Message-Digest Algorithm is a cryptographic hash function. It uses a Merkle tree-like structure to allow for immense parallel computation of hashes for very long inputs. Authors claim a performance of 28 cycles per byte for MD6-256 on an Intel Core 2 Duo and provable resistance against differential cryptanalysis. The source code of the reference implementation was released under MIT license.
Speeds in excess of 1 GB/s have been reported to be possible for long messages on 16-core CPU architecture.
In December 2008, Douglas Held of Fortify Software discovered a buffer overflow in the original MD6 hash algorithm's reference implementation. This error was later made public by Ron Rivest on 19 February 2009, with a release of a corrected reference implementation in advance of the Fortify Report.
MD6 was submitted to the NIST SHA-3 competition. However, on July 1, 2009, Rivest posted a comment at NIST that MD6 is not yet ready to be a candidate for SHA-3 because of speed issues, a "gap in the proof that the submitted version of MD6 is resistant to differential attacks", and an inability to supply such a proof for a faster reduced-round version, although Rivest also stated at the MD6 website that it is not withdrawn formally. MD6 did not advance to the second round of the SHA-3 competition. In September 2011, a paper presenting an improved proof that MD6 and faster reduced-round versions are resistant to differential attacks was posted to the MD6 website.

## Related

- [[Grøstl]]
- [[JH (hash function)]]
- [[NIST hash function competition]]
- [[SANDstorm hash]]
- [[SHA-3]]
- [[Skein (hash function)]]
- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Collision attack]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MD6