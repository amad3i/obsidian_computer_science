---
title: "Cryptovirology"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Cryptovirology"
wikipedia_categories: ["Computer viruses", "Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[BadBIOS]]"]
---

# Cryptovirology

Cryptovirology refers to the study of cryptography use in malware, such as ransomware and asymmetric backdoors. Traditionally, cryptography and its applications are defensive in nature, and provide privacy, authentication, and security to users. Cryptovirology employs a twist on cryptography, showing that it can also be used offensively. It can be used to mount extortion based attacks that cause loss of access to information, loss of confidentiality, and information leakage, tasks which cryptography typically prevents.
The field was born with the observation that public-key cryptography can be used to break the symmetry between what an antivirus analyst sees regarding malware and what the attacker sees. The antivirus analyst sees a public key contained in the malware, whereas the attacker sees the public key contained in the malware as well as the corresponding private key (outside the malware) since the attacker created the key pair for the attack. The public key allows the malware to perform trapdoor one-way operations on the victim's computer that only the attacker can undo.

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
- [[BadBIOS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cryptovirology