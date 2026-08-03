---
title: "Entropic security"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Entropic_security"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Entropic security

Entropic security is a security definition used in the field of cryptography. Modern encryption schemes are generally required to protect communications even when the attacker has substantial information about the messages being encrypted. For example, even if an attacker knows that an intercepted ciphertext encrypts either the message "Attack" or the message "Retreat", a semantically secure encryption scheme will prevent the attacker from learning which of the two messages is encrypted. However, definitions such as semantic security are too strong to achieve with certain specialized encryption schemes. Entropic security is a weaker definition that can be used in the special case where an attacker has very little information about the messages being encrypted.
It is well known that certain types of encryption algorithm cannot satisfy definitions such as semantic security: for example, deterministic encryption algorithms can never be semantically secure. Entropic security definitions relax these definitions to cases where the message space has substantial entropy (from an adversary's point of view). Under this definition it is possible to prove security of deterministic encryption.
Note that in practice entropically-secure encryption algorithms are only "secure" provided that the message distribution possesses high entropy from any reasonable adversary's perspective. This is an unrealistic assumption for a general encryption scheme, since one cannot assume that all likely users will encrypt high-entropy messages. For these schemes, stronger definitions (such as semantic security or indistinguishability under adaptive chosen ciphertext attack) are appropriate. However, there are special cases in which it is reasonable to require high entropy messages. For example, encryption schemes that encrypt only secret key material (e.g., key encapsulation or Key Wrap schemes) can be considered under an entropic security definition. A practical application of this result is the use of deterministic encryption algorithms for secure encryption of secret key material.
Russell and Wang formalized a definition of entropic security for encryption. Their definition resembles the semantic security definition when message spaces have highly-entropic distributions. In one formalization, the definition implies that an adversary given the ciphertext will be unable to compute any predicate on the ciphertext with (substantially) greater probability than an adversary who does not possess the ciphertext. Dodis and Smith later proposed alternate definitions and showed equivalence.

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

- Wikipedia: https://en.wikipedia.org/wiki/Entropic_security