---
title: "Key-agreement protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Key-agreement_protocol"
wikipedia_categories: ["Cryptography", "Key-agreement protocols"]
related: ["[[Password-authenticated key agreement]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]"]
---

# Key-agreement protocol

In cryptography, a key-agreement protocol is a protocol whereby two (or more) parties generate a cryptographic key as a function of information provided by each honest party so that no party can predetermine the resulting value.
In particular, all honest participants influence the outcome. A key-agreement protocol is a specialisation of a key-exchange protocol.
At the completion of the protocol, all parties share the same key. A key-agreement protocol precludes undesired third parties from forcing a key choice on the agreeing parties. A secure key agreement can ensure confidentiality and data integrity in communications systems, ranging from simple messaging applications to complex banking transactions.
Secure agreement is defined relative to a security model, for example the Universal Model. More generally, when evaluating protocols, it is important to state security goals and the security model. For example, it may be required for the session key to be authenticated. A protocol can be evaluated for success only in the context of its goals and attack model. An example of an adversarial model is the Dolev–Yao model. 
In many key exchange systems, one party generates the key, and sends that key to the other party; the other party has no influence on the key.

## Related

- [[Password-authenticated key agreement]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Key-agreement_protocol