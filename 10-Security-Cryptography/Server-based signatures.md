---
title: "Server-based signatures"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Server-based_signatures"
wikipedia_categories: ["Cryptography"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Server-based signatures

In cryptography, server-based signatures are digital signatures in which a publicly available server participates in the signature creation process. This is in contrast to conventional digital signatures that are based on public-key cryptography and public-key infrastructure. With that, they assume that signers use their personal trusted computing bases for generating signatures without any communication with servers.
Four different classes of server based signatures have been proposed:
1. Lamport One-Time Signatures. Proposed in 1979 by Leslie Lamport. Lamport one-time signatures are based on cryptographic hash functions. For signing a message, the signer just sends a list of hash values (outputs of a hash function) to a publishing server and therefore the signature process is very fast, though the size of the signature is many times larger, compared to ordinary public-key signature schemes.
2. On-line/off-line Digital Signatures. First proposed in 1989 by Even, Goldreich and Micali in order to speed up the signature creation procedure, which is usually much more time-consuming than verification. In case of RSA, it may be one thousand times slower than verification. On-line/off-line digital signatures are created in two phases. The first phase is performed off-line, possibly even before the message to be signed is known. The second (message-dependent) phase is performed on-line  and involves communication with a server. In the first (off-line) phase, the signer uses a conventional public-key digital signature scheme to sign a public key of the Lamport one-time signature scheme. In the second phase, a message is signed by using the Lamport signature scheme. Some later works 
 have improved the efficiency of the original solution by Even et al.
3. Server-Supported Signatures (SSS). Proposed in 1996 by Asokan, Tsudik and Waidner in order to delegate the use of time-consuming operations of asymmetric cryptography from clients (ordinary users) to a server. For ordinary users, the use of asymmetric cryptography is limited to signature verification, i.e. there is no pre-computation phase like in the case of on-line/off-line signatures.  The main motivation was the use of low-performance mobile devices for creating digital signatures, considering that such devices could be too slow for creating ordinary public-key digital signatures, such as RSA. Clients use hash chain based authentication  to send their messages to a signature server in an authenticated way and the server then creates a digital signature by using an ordinary public-key digital signature scheme. In SSS, signature servers are not assumed to be Trusted Third Parties (TTPs) because the transcript of the hash chain authentication phase can be used for non repudiation  purposes. In SSS, servers cannot create signatures in the name of their clients.
4. Delegate Servers (DS). Proposed in 2002 by Perrin, Bruns, Moreh and Olkin in order to reduce the problems and costs related to individual private keys. In their solution, clients (ordinary users) delegate their private cryptographic operations to a Delegation Server (DS). Users authenticate to DS and request to sign messages on their behalf by using the server's own private key. The main motivation behind DS was that private keys are difficult for ordinary users to use and easy for attackers to abuse. Private keys are not memorable like passwords or derivable from persons like biometrics, and cannot be entered from keyboards like passwords. Private keys are mostly stored as files in computers or on smart-cards, that may be stolen by attackers and abuse off-line. In 2003, Buldas and Saarepera proposed a two-level architecture of delegation servers that addresses the trust issue by replacing trust with threshold trust via the use of threshold cryptosystems.

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

- Wikipedia: https://en.wikipedia.org/wiki/Server-based_signatures