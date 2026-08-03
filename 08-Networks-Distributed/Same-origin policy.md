---
title: "Same-origin policy"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Same-origin_policy"
wikipedia_categories: ["Computer network security", "Computer security procedures", "Computer security standards", "Hypertext Transfer Protocol headers", "Web applications"]
related: ["[[Common Vulnerability Scoring System]]", "[[Defense in depth (computing)]]", "[[HTTP Strict Transport Security]]", "[[Network security policy]]", "[[Offensive Security]]", "[[Security controls]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[ActivityPub]]", "[[Administrative domain]]"]
---

# Same-origin policy

In computing, the same-origin policy (SOP) is a concept in the web application security model. Under the policy, a web browser permits scripts contained in a first web page to access data in a second web page, but only if both web pages have the same origin. An origin is defined as a combination of URI scheme, host name, and port number. This policy prevents a malicious script on one page from obtaining access to sensitive data on another web page through that page's Document Object Model (DOM).
This mechanism bears a particular significance for modern web applications that extensively depend on HTTPS cookies to maintain authenticated user sessions, as servers act based on the HTTP cookie information to reveal sensitive information or perform state-changing actions. A strict separation between content provided by unrelated sites must be maintained on the client-side to prevent the loss of data confidentiality or integrity.
The same-origin policy applies only to scripts. This means that resources such as images, CSS, and dynamically loaded scripts can be accessed across origins via the corresponding HTML tags (with fonts being a notable exception). Attacks take advantage of the fact that the same origin policy does not apply to HTML tags.
There are some mechanisms available to relax the SOP; one of them is cross-origin resource sharing (CORS).

## Related

- [[Common Vulnerability Scoring System]]
- [[Defense in depth (computing)]]
- [[HTTP Strict Transport Security]]
- [[Network security policy]]
- [[Offensive Security]]
- [[Security controls]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[ActivityPub]]
- [[Administrative domain]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Same-origin_policy