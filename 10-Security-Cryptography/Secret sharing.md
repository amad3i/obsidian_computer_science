---
title: "Secret sharing"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Secret_sharing"
wikipedia_categories: ["Cryptography", "Secret sharing"]
related: ["[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]", "[[Backdoor (computing)]]", "[[Batch cryptography]]"]
---

# Secret sharing

Secret sharing (also called secret splitting) refers to methods for distributing a secret among a group, in such a way that no individual holds any intelligible information about the secret, but when a sufficient number of individuals combine their 'shares', the secret may be reconstructed. Whereas insecure secret sharing allows an attacker to gain more information with each share, secure secret sharing is 'all or nothing' (where 'all' means the necessary number of shares).
In one type of secret sharing scheme there is one dealer and n players. The dealer gives a share of the secret to the players, but only when specific conditions are fulfilled will the players be able to reconstruct the secret from their shares. The dealer accomplishes this by giving each player a share in such a way that any group of t (for threshold) or more players can together reconstruct the secret but no group of fewer than t players can. Such a system is called a (t, n)-threshold scheme (sometimes it is written as an (n, t)-threshold scheme).
Secret sharing was invented independently by Adi Shamir and George Blakley in 1979.

## Related

- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]
- [[Backdoor (computing)]]
- [[Batch cryptography]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Secret_sharing