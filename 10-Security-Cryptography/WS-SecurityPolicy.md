---
title: "WS-SecurityPolicy"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/WS-SecurityPolicy"
wikipedia_categories: ["Computer security", "Security technology", "Web service specifications"]
related: ["[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]", "[[Attack path management]]", "[[Automated penetration testing]]", "[[Automotive security]]"]
---

# WS-SecurityPolicy

WS-Security Policy is a web services specification, created by IBM and 12 co-authors, that has become an OASIS standard as of version 1.2. It extends the fundamental security protocols specified by the WS-Security, WS-Trust and WS-Secure Conversation by offering mechanisms to represent the capabilities and requirements of web services as policies. Security policy assertions are based on the WS-Policy framework. 
Policy assertions can be used to require more generic security attributes like transport layer security <TransportBinding>, message level security <AsymmetricBinding> or timestamps, and specific attributes like token types. 
Most policy assertion can be found in following categories:

Protection assertions identify the elements of a message that are required to be signed, encrypted or existent.
Token assertions specify allowed token formats (SAML, X509, Username etc.).
Security binding assertions control basic security safeguards like transport and message level security, cryptographic algorithm suite and required timestamps.
Supporting token assertions add functions like user sign-on using a username token.
Policies can be used to drive development tools to generate code with certain capabilities, or may be used at runtime to negotiate the security aspects of web service communication. Policies may be attached to WSDL elements such as service, port, operation and message, as defined in WS Policy Attachment.

## Related

- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]
- [[Attack path management]]
- [[Automated penetration testing]]
- [[Automotive security]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/WS-SecurityPolicy