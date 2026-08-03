---
title: "HTTP Strict Transport Security"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security"
wikipedia_categories: ["Computer security standards", "Cryptography", "Hypertext Transfer Protocol headers", "Transport Layer Security"]
related: ["[[BREACH]]", "[[POODLE]]", "[[S-MIME]]", "[[Same-origin policy]]", "[[Server-Gated Cryptography]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]"]
---

# HTTP Strict Transport Security

HTTP Strict Transport Security (HSTS) is a policy mechanism that helps to protect websites against man-in-the-middle attacks such as protocol downgrade attacks and cookie hijacking. It allows web servers to declare that web browsers (or other complying user agents) should automatically interact with it using only HTTPS connections, which provide Transport Layer Security (TLS/SSL), unlike the insecure HTTP used alone. HSTS is an IETF standards track protocol and is specified in RFC 6797.
The HSTS Policy is communicated by the server to the user agent via an HTTP response header field named Strict-Transport-Security. HSTS Policy specifies a period of time during which the user agent should only access the server in a secure fashion. Websites using HSTS often do not accept clear text HTTP, either by rejecting connections over HTTP or systematically redirecting users to HTTPS (though this is not required by the specification). The consequence of this is that a user-agent not capable of doing TLS will not be able to connect to the site.
The protection normally only applies after a user has visited the site at least once, relying on the principle of "trust on first use". The way this protection works is that when a user entering or selecting an HTTP (not HTTPS) URL to the site, the client, such as a Web browser, will automatically upgrade to HTTPS without making an HTTP request, thereby preventing any HTTP man-in-the-middle attack from occurring. To counteract this problem, an HSTS preload list maintained by Google Chrome and used by other major web browsers is maintained. If a domain is on this list, the browser skips the initial request and encrypts all communication immediately. Additional domains can be registered at no cost.

## Related

- [[BREACH]]
- [[POODLE]]
- [[S-MIME]]
- [[Same-origin policy]]
- [[Server-Gated Cryptography]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security