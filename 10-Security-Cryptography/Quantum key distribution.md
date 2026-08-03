---
title: "Quantum key distribution"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Quantum_key_distribution"
wikipedia_categories: ["Quantum cryptography", "Quantum information science"]
related: ["[[B92 protocol]]", "[[BB84]]", "[[High-dimensional quantum key distribution]]", "[[Quantum capacity]]", "[[Quantum readout]]", "[[Relativistic quantum cryptography]]", "[[Six-state protocol]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]"]
---

# Quantum key distribution

Quantum key distribution (QKD) is a secure communication method that implements a cryptographic protocol based on the laws of quantum mechanics, specifically quantum entanglement, the measurement-disturbance principle, and the no-cloning theorem. The goal of QKD is to enable two parties to produce a shared random secret key known only to them, which then can be used to encrypt and decrypt messages. This means, when QKD is correctly implemented, one would need to violate fundamental physical principles to break a quantum protocol. The QKD process should not be confused with quantum cryptography in general.
An important and unique property of QKD is the ability of the two communicating users to detect the presence of any third party trying to gain knowledge of the key. This results from a fundamental aspect of quantum mechanics: the process of measuring a quantum system in general disturbs the system. This means, a third party attempting to eavesdrop on the key must in some way measure it, thus introducing detectable anomalies, thereby revealing the presence of the eavesdropper. This unique property ensures that the distributed keys remain secure, as any attempt at interception will be immediately apparent and will invalidate the exchanged key. By using quantum superpositions or quantum entanglement and transmitting information in quantum states, a communication system can be implemented that detects eavesdropping. If the level of eavesdropping is below a certain threshold, a key can be produced that is guaranteed to be secure (i.e., the eavesdropper has no information about it). Otherwise no secure key is possible, and communication is aborted.
The security of encryption that uses quantum key distribution relies on the foundations of quantum mechanics, in contrast to traditional public key cryptography, which relies on the computational difficulty of certain mathematical functions, which although conjectured to be strong has not to date been formally proved. In contrast, QKD has provable security based on information theory, and forward secrecy.
The main drawback of quantum-key distribution is that it usually relies on having an authenticated classical channel of communication. In modern cryptography, having an authenticated classical channel means that one already has exchanged either a symmetric key of sufficient length or public keys of sufficient security level. With such information already available, in practice one can achieve authenticated and sufficiently secure communication without using QKD, such as by using the Galois/Counter Mode of the Advanced Encryption Standard. Thus QKD does the work of a stream cipher at many times the cost.
Quantum key distribution is used to produce and distribute only a key, not to transmit any message data. This key can then be used with any chosen encryption algorithm to encrypt (and decrypt) a message, which can then be transmitted over a standard communication channel. The algorithm most commonly associated with QKD is the one-time pad, as it is provably secure when used with a secret, random key. In real-world situations, it is often also used with encryption using symmetric key algorithms like the Advanced Encryption Standard algorithm.

## Related

- [[B92 protocol]]
- [[BB84]]
- [[High-dimensional quantum key distribution]]
- [[Quantum capacity]]
- [[Quantum readout]]
- [[Relativistic quantum cryptography]]
- [[Six-state protocol]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quantum_key_distribution