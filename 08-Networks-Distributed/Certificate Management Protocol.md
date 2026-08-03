---
title: "Certificate Management Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Certificate_Management_Protocol"
wikipedia_categories: ["Cryptographic protocols", "Internet Standards", "Internet protocols", "Public key infrastructure"]
related: ["[[Certificate Management over CMS]]", "[[Online Certificate Status Protocol]]", "[[Enrollment over Secure Transport]]", "[[OCSP stapling]]", "[[SCVP]]", "[[Simple Certificate Enrollment Protocol]]", "[[AS1 (networking)]]", "[[AS2]]", "[[Automatic Certificate Management Environment]]", "[[Berkeley r-commands]]"]
---

# Certificate Management Protocol

The Certificate Management Protocol (CMP) is an Internet protocol standardized by the IETF used for obtaining X.509 public-key certificates in a PKI.
CMP is a very feature-rich and flexible protocol.
So far it is the only protocol with support of all types of cryptography. This includes KEM keys, which have become more important for post-quantum cryptography (PQC).
CMP messages are self-contained, which makes the protocol independent of the transport mechanism and provides end-to-end security also over multiple hops. This distinguishes CMP and CMC from other certificate enrollment protocols including EST.
CMP messages are defined in ASN.1 syntax and encoded using the DER method.
CMP is described in RFC 9810. Enrollment request messages employ the Certificate Request Message Format (CRMF), described in RFC 4211 and updated in RFC 9045.
The only other protocol so far using CRMF is Certificate Management over CMS (CMC), described in RFC 5273.

## Related

- [[Certificate Management over CMS]]
- [[Online Certificate Status Protocol]]
- [[Enrollment over Secure Transport]]
- [[OCSP stapling]]
- [[SCVP]]
- [[Simple Certificate Enrollment Protocol]]
- [[AS1 (networking)]]
- [[AS2]]
- [[Automatic Certificate Management Environment]]
- [[Berkeley r-commands]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Certificate_Management_Protocol