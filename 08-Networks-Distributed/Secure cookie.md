---
title: "Secure cookie"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Secure_cookie"
wikipedia_categories: ["Internet privacy"]
related: ["[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]", "[[2023 Bangladesh Government website data breach]]", "[[Anonymous blog]]", "[[Behavioral retargeting]]", "[[Big data ethics]]", "[[Canvas fingerprinting]]", "[[Click analytics]]", "[[Client Hints]]"]
---

# Secure cookie

Secure cookie is a type of an HTTP cookie that has the Secure attribute set, which limits the scope of the cookie to "secure" channels (where "secure" is defined by the user agent, typically web browser). When a cookie has the Secure attribute, the user agent will include the cookie in an HTTP request only if the request is transmitted over a secure channel (typically HTTPS).
Although seemingly useful for protecting cookies from active network attackers, the Secure attribute protects only the cookie's confidentiality. An active network attacker can overwrite Secure cookies from an insecure channel, disrupting their integrity. This issue is officially referred to as Weak Integrity. However, some browsers, including Chrome 52 and higher and Firefox 52 and higher, forgo this specification in favor of better security and forbid insecure sites (HTTP) from setting cookies with the Secure directive.
Even with Secure, some sources recommend that sensitive information never be stored in cookies, on the premise that they are inherently insecure and this flag can't offer real protection. Secure attribute is not the only protection mechanism for cookies, there are also HttpOnly and SameSite attributes. The HttpOnly attribute restricts the cookie from being accessed by, for instance, JavaScript, while the SameSite attribute only allows the cookie to be sent to the application if the request originated from the same domain.

## Related

- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]
- [[2023 Bangladesh Government website data breach]]
- [[Anonymous blog]]
- [[Behavioral retargeting]]
- [[Big data ethics]]
- [[Canvas fingerprinting]]
- [[Click analytics]]
- [[Client Hints]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Secure_cookie