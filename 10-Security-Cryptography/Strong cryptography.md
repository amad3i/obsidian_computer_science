---
title: "Strong cryptography"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Strong_cryptography"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Strong cryptography

Strong cryptography or cryptographically strong are general terms used to designate the cryptographic algorithms that, when used correctly, provide a very high (usually insurmountable) level  of protection against any eavesdropper, including the government agencies. There is no precise definition of the boundary line between the strong cryptography and (breakable) weak cryptography, as this border constantly shifts due to improvements in hardware and cryptanalysis techniques. These improvements eventually place the capabilities once available only to the NSA within the reach of a skilled individual, so in practice there are only two levels of cryptographic security, "cryptography that will stop your kid sister from reading your files, and cryptography that will stop major governments from reading your files" (Bruce Schneier).
The strong cryptography algorithms have high security strength, for practical purposes usually defined as a number of bits in the key. For example, the United States government, when dealing with export control of encryption, considered as of 1999 any implementation of the symmetric encryption algorithm with the key length above 56 bits or its public key equivalent to be strong and thus potentially a subject to the export licensing. To be strong, an algorithm needs to have a sufficiently long key and be free of known mathematical weaknesses, as exploitation of these effectively reduces the key size. At the beginning of the 21st century, the typical security strength of the strong symmetrical encryption algorithms is 128 bits (slightly lower values still can be strong, but usually there is little technical gain in using smaller key sizes).
Demonstrating the resistance of any cryptographic scheme to attack is a complex matter, requiring extensive testing and reviews, preferably in a public forum. Good algorithms and protocols are required (similarly, good materials are required to construct a strong building), but good system design and implementation is needed as well: "it is possible to build a cryptographically weak system using strong algorithms and protocols" (just like the use of good materials in construction does not guarantee a solid structure). Many real-life systems turn out to be weak when the strong cryptography is not used properly, for example, random nonces are reused A successful attack might not even involve algorithm at all, for example, if the key is generated from a password, guessing a weak password is easy and does not depend on the strength of the cryptographic primitives. A user can become the weakest link in the overall picture, for example, by sharing passwords and hardware tokens with the colleagues.

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

- Wikipedia: https://en.wikipedia.org/wiki/Strong_cryptography