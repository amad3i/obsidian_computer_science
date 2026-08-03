---
title: "Verifiable secret sharing"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Verifiable_secret_sharing"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Verifiable secret sharing

In cryptography, a secret sharing scheme is verifiable if auxiliary information is included that allows players to verify their shares as consistent. More formally, verifiable secret sharing ensures that even if the dealer is malicious there is a well-defined secret that the players can later reconstruct. (In standard secret sharing, the dealer is assumed to be honest.)
The concept of verifiable secret sharing (VSS) was first introduced in 1985 by Benny Chor, Shafi Goldwasser, Silvio Micali and Baruch Awerbuch.
In a VSS protocol a distinguished player who wants to share the secret is referred to as the dealer. The protocol consists of two phases: a sharing phase and a reconstruction phase.
Sharing: Initially the dealer holds secret as input and each player holds an independent random input. The sharing phase may consist of several rounds. At each round each player can privately send messages to other players and can also broadcast a message. Each message sent or broadcast by a player is determined by its input, its random input and messages received from other players in previous rounds.
Reconstruction: In this phase each player provides its entire view from the sharing phase and a reconstruction function is applied and is taken as the protocol's output.
An alternative definition given by Oded Goldreich defines VSS as a secure multi-party protocol for computing the randomized functionality corresponding to some (non-verifiable) secret sharing scheme. This definition is stronger than that of the other definitions and is very convenient to use in the context of general secure multi-party computation.
Verifiable secret sharing is important for secure multiparty computation.  Multiparty computation is typically accomplished by making secret shares of the inputs, and manipulating the shares to compute some function.  To handle "active" adversaries (that is, adversaries that corrupt nodes and then make them deviate from the protocol), the secret sharing scheme needs to be verifiable to prevent the deviating nodes from throwing off the protocol.

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

- Wikipedia: https://en.wikipedia.org/wiki/Verifiable_secret_sharing