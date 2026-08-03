---
title: "CryptGenRandom"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/CryptGenRandom"
wikipedia_categories: ["Cryptographic algorithms", "Cryptographically secure pseudorandom number generators", "Microsoft Windows security technology", "Microsoft application programming interfaces", "Pseudorandom number generators"]
related: ["[[Cryptographically secure pseudorandom number generator]]", "[[Feedback with Carry Shift Registers]]", "[[Linear-feedback shift register]]", "[[ADO.NET]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]"]
---

# CryptGenRandom

CryptGenRandom is a cryptographically secure pseudorandom number generator function that is included in Microsoft CryptoAPI. In Win32 programs, Microsoft recommended its use anywhere random number generation is needed (it has since been replaced by BCryptGenRandom, see below). The kernel32 equivalent is RtlGenRandom.
A 2007 paper from Hebrew University suggested security problems in the Windows 2000 implementation of CryptGenRandom (assuming the attacker has control of the machine). Microsoft later acknowledged that the same problems exist in Windows XP, but not in Vista. Microsoft released a fix for the bug with Windows XP Service Pack 3 in mid-2008.
CryptGenRandom is deprecated as it belongs to the deprecated Windows CryptoAPI. The modern Cryptography API: Next Generation (CNG) replacement is BCryptGenRandom (and the underlying functions ProcessPrng and SystemPrng).

## Related

- [[Cryptographically secure pseudorandom number generator]]
- [[Feedback with Carry Shift Registers]]
- [[Linear-feedback shift register]]
- [[ADO.NET]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CryptGenRandom