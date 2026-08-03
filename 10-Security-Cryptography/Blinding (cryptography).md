---
title: "Blinding (cryptography)"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Blinding_(cryptography)"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Blinding (cryptography)

In cryptography, blinding first became known in the context of blind signatures, where the message author blinds the message with a random blinding factor, the signer then signs it and the message author "unblinds" it; signer and message author are different parties.
Since the late 1990s, blinding mostly refers to countermeasures against side-channel attacks on encryption devices, where the random blinding and the "unblinding" happen on the encryption devices. The techniques used for blinding signatures were adapted to prevent attackers from knowing the input to the modular exponentiation function for Diffie-Hellman or RSA.
Blinding must be applied with care, for example Rabin–Williams signatures. If blinding is applied to the formatted message but the random value does not honor Jacobi requirements on p and q, then it could lead to private key recovery. A demonstration of the recovery can be seen in CVE-2015-2141 discovered by Evgeny Sidorov.
Side-channel attacks allow an adversary to recover information about the input to a cryptographic operation within an  asymmetric encryption scheme, by measuring something other than the algorithm's result, e.g., power consumption, computation time, or radio-frequency emanations by a device.  Typically these attacks depend on the attacker knowing the characteristics of the algorithm, as well as (some) inputs.  In this setting, blinding serves to alter the algorithm's input into some unpredictable state.  Depending on the characteristics of the blinding function, this can prevent some or all leakage of useful information.  Note that security depends also on the resistance of the blinding functions themselves to side-channel attacks.

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

- Wikipedia: https://en.wikipedia.org/wiki/Blinding_(cryptography)