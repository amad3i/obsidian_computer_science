---
title: "Sender Policy Framework"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Sender_Policy_Framework"
wikipedia_categories: ["Anti-spam", "Email authentication", "Internet architecture", "Internet governance", "Internet protocols", "Network addressing"]
related: ["[[Authenticated Received Chain]]", "[[DomainKeys Identified Mail]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Domain Name System]]", "[[Forward-confirmed reverse DNS]]", "[[Ident protocol]]", "[[Identifier-Locator Network Protocol]]"]
---

# Sender Policy Framework

Sender Policy Framework (SPF) is an email authentication method that allows checking whether the sending mail server is authorized to originate mail from the email sender's domain. This authentication only applies to the email sender listed in the "envelope from" field during the initial SMTP connection. If the email is bounced, a message is sent to this address, and for downstream transmission it typically appears in the "Return-Path" header. To authenticate the email address which is actually visible to recipients on the "From:" line, other technologies, such as DMARC, must be used. Forgery of this address is known as email spoofing, and is often used in phishing and email spam.
The list of authorized sending hosts and IP addresses for a domain is published in the DNS records for that domain. Sender Policy Framework is defined in RFC 7208 dated April 2014 as a "proposed standard".

## Related

- [[Authenticated Received Chain]]
- [[DomainKeys Identified Mail]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Domain Name System]]
- [[Forward-confirmed reverse DNS]]
- [[Ident protocol]]
- [[Identifier-Locator Network Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sender_Policy_Framework