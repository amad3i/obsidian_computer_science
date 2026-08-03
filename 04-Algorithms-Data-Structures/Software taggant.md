---
title: "Software taggant"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Software_taggant"
wikipedia_categories: ["Computer security stubs", "Cryptographic algorithms"]
related: ["[[Alert correlation]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[Banner grabbing]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Centurion Guard]]", "[[Ciphertext stealing]]"]
---

# Software taggant

A software taggant is a cryptographic signature added to software that enables positive origin identification and integrity of programs. Software taggants use standard public key infrastructure (PKI) techniques and were introduced by the Industry Connections Security Group of IEEE in an attempt to control proliferation of malware obfuscated via executable compression (runtime packers).
The concept of a PKI-based system to mitigate runtime packer abuse was introduced in 2010 and described in a Black Hat Briefings presentation by Mark Kennedy and Igor Muttik. The term was proposed by Arun Lakhotia (due to its similarities with chemical taggants) who also analyzed the economics of a packer ecosystem.
A software taggant is a form of code signing somewhat similar to Microsoft's Authenticode. The key differences between a software taggant and Authenticode are that the transparent and free addition of a software taggant for the end user of a runtime packer. Also, a software taggant may cover small critical areas of the program to minimize the cost of software integrity checking. To contrast, Authenticode always covers nearly the entire file so the cost of checking linearly depends on the file size.
The software taggant project is run by Industry Connections Security Group and has open-source nature - it is hosted on GitHub and relies on OpenSSL. Software taggants also help to legitimate software from malware which also utilize anti-tampering methods.

## Related

- [[Alert correlation]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[Banner grabbing]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Centurion Guard]]
- [[Ciphertext stealing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Software_taggant