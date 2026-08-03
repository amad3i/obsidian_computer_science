---
title: "Universal 2nd Factor"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Universal_2nd_Factor"
wikipedia_categories: ["Authentication protocols", "Computer access control protocols", "Internet Standards", "Internet protocols"]
related: ["[[RADIUS]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Challenge-Handshake Authentication Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]"]
---

# Universal 2nd Factor

Universal 2nd Factor (U2F) is an open standard that strengthens and simplifies two-factor authentication (2FA) using specialized Universal Serial Bus (USB), near-field communication (NFC), or Bluetooth Low Energy (BLE) devices based on similar security technology found in smart cards. It is superseded by the FIDO2 Project, which includes the W3C Web Authentication (WebAuthn) standard and the FIDO Alliance's Client to Authenticator Protocol 2 (CTAP2).
While initially developed by Google and Yubico, with contribution from NXP Semiconductors, the standard is now hosted by the FIDO Alliance.

While time-based one-time password (TOTPs) (e.g. 6-digit codes generated on Google Authenticator) were a significant improvement over SMS-based security codes, a number of security vulnerabilities were still possible to exploit, which U2F sought to improve. Specifically: 

In terms of disadvantages, one significant difference and potential drawback to be considered regarding hardware-based U2F solutions is that unlike with TOTP shared-secret methods, there is no possibility of "backing up" recovery codes or shared secrets.  If a hardware duplicate or alternative hardware key is not kept and the original U2F hardware key is lost, no recovery of the key is possible (because the private key exists only in hardware).  Therefore, for services that do not provide any alternative account recovery method, the use of U2F should be carefully considered.

## Related

- [[RADIUS]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Challenge-Handshake Authentication Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Universal_2nd_Factor