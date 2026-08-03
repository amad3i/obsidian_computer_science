---
title: "Password Authentication Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Password_Authentication_Protocol"
wikipedia_categories: ["Authentication protocols", "Internet protocols", "Password authentication"]
related: ["[[Challenge-Handshake Authentication Protocol]]", "[[Password-authenticated key agreement]]", "[[Simultaneous Authentication of Equals]]", "[[Universal 2nd Factor]]", "[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]"]
---

# Password Authentication Protocol

Password Authentication Protocol (PAP) is a password-based authentication protocol used by Point-to-Point Protocol (PPP) to validate users. PAP is specified in RFC 1334.
Almost all network operating systems support PPP with PAP, as do most network access servers. PAP is also used in PPPoE, for authenticating DSL users.
As the Point-to-Point Protocol (PPP) sends data unencrypted and "in the clear", PAP is vulnerable to any attacker who can observe the PPP session.  An attacker can see the users name, password, and any other information associated with the PPP session. Some additional security can be gained on the PPP link by using CHAP or EAP. However, there are always tradeoffs when choosing an authentication method, and there is no single answer for which is more secure.
When PAP is used in PPP, it is considered a weak authentication scheme. Weak schemes are simpler and have lighter computational overhead than more complex schemes, such as Transport Layer Security (TLS), but they are much more vulnerable to attack. Weak schemes are used where the transport layer is expected to be physically secure, such as a home DSL link. Where the transport layer is not physically secure a system such as TLS or Internet Protocol Security (IPsec) is used instead.

## Related

- [[Challenge-Handshake Authentication Protocol]]
- [[Password-authenticated key agreement]]
- [[Simultaneous Authentication of Equals]]
- [[Universal 2nd Factor]]
- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Password_Authentication_Protocol