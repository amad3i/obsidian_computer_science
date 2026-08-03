---
title: "Online Certificate Status Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Online_Certificate_Status_Protocol"
wikipedia_categories: ["Certificate revocation", "Cryptographic protocols", "Internet Standards", "Internet protocols", "Public key infrastructure", "Transport Layer Security"]
related: ["[[OCSP stapling]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Enrollment over Secure Transport]]", "[[SCVP]]", "[[Simple Certificate Enrollment Protocol]]", "[[AS1 (networking)]]", "[[AS2]]", "[[Automatic Certificate Management Environment]]", "[[Berkeley r-commands]]"]
---

# Online Certificate Status Protocol

The Online Certificate Status Protocol (OCSP) is an Internet protocol used for obtaining the revocation status of an X.509 digital certificate. It was created as an alternative to certificate revocation lists (CRL), specifically addressing certain problems associated with using CRLs in a public key infrastructure (PKI). Messages communicated via OCSP are encoded in ASN.1 and are usually communicated over HTTP. The "request/response" nature of these messages leads to OCSP servers being termed OCSP responders.
Some web browsers (e.g., Firefox) use OCSP to validate HTTPS certificates, while others have disabled it. Most OCSP revocation statuses on the Internet disappear soon after certificate expiration.
Certificate authorities (CAs) were previously required by the CA/Browser Forum to provide OCSP service, but this requirement was removed in July 2023, making OCSP optional and CRLs required again. On August 6, 2025, Let's Encrypt announced that OCSP services will be shut down due to privacy concerns.

## Related

- [[OCSP stapling]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Enrollment over Secure Transport]]
- [[SCVP]]
- [[Simple Certificate Enrollment Protocol]]
- [[AS1 (networking)]]
- [[AS2]]
- [[Automatic Certificate Management Environment]]
- [[Berkeley r-commands]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Online_Certificate_Status_Protocol