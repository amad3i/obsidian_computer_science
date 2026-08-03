---
title: "OCSP stapling"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/OCSP_stapling"
wikipedia_categories: ["Certificate revocation", "Cryptographic protocols", "Internet Standards", "Internet protocols", "Transport Layer Security"]
related: ["[[Online Certificate Status Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[SCVP]]", "[[AS1 (networking)]]", "[[AS2]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]"]
---

# OCSP stapling

The Online Certificate Status Protocol (OCSP) stapling, formally known as the TLS Certificate Status Request extension, is a standard for checking the revocation status of X.509 digital certificates. It allows the presenter of a certificate to bear the resource cost involved in providing Online Certificate Status Protocol (OCSP) responses by appending ("stapling") a time-stamped OCSP response signed by the CA (certificate authority) to the initial TLS handshake, eliminating the need for clients to contact the CA, with the aim of improving both security and performance.

## Related

- [[Online Certificate Status Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[SCVP]]
- [[AS1 (networking)]]
- [[AS2]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/OCSP_stapling