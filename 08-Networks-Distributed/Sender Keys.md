---
title: "Sender Keys"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Sender_Keys"
wikipedia_categories: ["Cryptography", "Internet privacy", "Secure communication"]
related: ["[[End-to-end encryption]]", "[[Messaging Layer Security]]", "[[Blacker (security)]]", "[[CryptoParty]]", "[[Cypherpunks (book)]]", "[[Red-black concept]]", "[[Secure channel]]", "[[Secure communication]]", "[[Secure voice]]", "[[Zero-knowledge service]]"]
---

# Sender Keys

In cryptography, Sender Keys is a variant of the Signal Protocol used in end-to-end encryption used in instant messaging. Sender Keys is used for group chats. Applications using it have included Signal, Matrix, WhatsApp, Session, and Facebook Messenger.
In order to scale to large groups, the protocol takes advantage of server-side fan-out and avoids computing a shared group key. The algorithm relies upon secure pairwise communication channels between peers that provide confidentiality and authentication. For example, an Authenticated Key Exchange algorithm such as Extended Triple Diffie-Hellman (X3DH) may be combined with the Double Ratchet Algorithm to construct such a channel in practice, as is the case with WhatsApp.
The protocol was described in a whitepaper from WhatsApp, and it is also related to the Messaging Layer Security standard.

## Related

- [[End-to-end encryption]]
- [[Messaging Layer Security]]
- [[Blacker (security)]]
- [[CryptoParty]]
- [[Cypherpunks (book)]]
- [[Red-black concept]]
- [[Secure channel]]
- [[Secure communication]]
- [[Secure voice]]
- [[Zero-knowledge service]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sender_Keys