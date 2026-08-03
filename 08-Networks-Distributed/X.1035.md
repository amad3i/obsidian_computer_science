---
title: "X.1035"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/X.1035"
wikipedia_categories: ["Applications of cryptography", "Computer networks", "Cryptographic protocols", "ITU-T X Series Recommendations", "ITU-T recommendations", "International standards", "Internet Standards", "Open standards"]
related: ["[[G.9963]]", "[[G.9970]]", "[[G.hn]]", "[[G.9972]]", "[[AS1 (networking)]]", "[[AS2]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Enrollment over Secure Transport]]", "[[OCSP stapling]]"]
---

# X.1035

ITU-T Recommendation X.1035 specifies a password-authenticated key agreement protocol that ensures mutual authentication of two parties by using a Diffie–Hellman key exchange to establish a symmetric cryptographic key. The use of Diffie-Hellman exchange ensures perfect forward secrecy—a property of a key establishment protocol that guarantees that compromise of a session key or long-term private key after a given session does not cause the compromise of any earlier session.
In X.1035, the exchange is protected from the man-in-the-middle attack. The authentication relies on a pre-shared secret (e.g., password), which is protected (i.e., remains unrevealed) to an eavesdropper preventing an off-line dictionary attack.
The protocol can be used in a wide variety of applications including those with pre-shared secrets based on possibly weak passwords.
X.1035 was approved on 13 February 2007 by ITU-T Study Group 17.

## Related

- [[G.9963]]
- [[G.9970]]
- [[G.hn]]
- [[G.9972]]
- [[AS1 (networking)]]
- [[AS2]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Enrollment over Secure Transport]]
- [[OCSP stapling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/X.1035