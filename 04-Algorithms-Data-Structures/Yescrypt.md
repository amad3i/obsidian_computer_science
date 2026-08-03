---
title: "Yescrypt"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Yescrypt"
wikipedia_categories: ["Cryptographic hash functions", "Cryptography stubs", "Key derivation functions"]
related: ["[[Argon2]]", "[[Ascon (cipher)]]", "[[Bcrypt]]", "[[Crypt (C)]]", "[[FORK-256]]", "[[Gimli (cipher)]]", "[[Grøstl]]", "[[HAIFA construction]]", "[[HAS-160]]", "[[HAS-V]]"]
---

# Yescrypt

yescrypt is a cryptographic key derivation function used for password hashing on Fedora Linux, Debian, Ubuntu, and Arch Linux. The function is more resistant to offline password-cracking attacks than SHA-512. It is based on scrypt.
It was designed by Alexander Peslyak, also known as Solar Designer, to be highly resistant to hardware-accelerated brute-force attacks. It features enhanced memory-hardness and "strongly sequential" processing, which reduces the threat of large-scale cracking attempts using GPUs, FPGAs, and ASICs. Attacks that rely on parallelization are made more resource-intensive by yescrypt requiring a substantial amount of RAM to compute a single hash. These security benefits and its scalability have led to its adoption as the default password-hashing scheme for several major Linux distributions, where it is identifiable in the /etc/shadow file by the $y$ prefix.

## Related

- [[Argon2]]
- [[Ascon (cipher)]]
- [[Bcrypt]]
- [[Crypt (C)]]
- [[FORK-256]]
- [[Gimli (cipher)]]
- [[Grøstl]]
- [[HAIFA construction]]
- [[HAS-160]]
- [[HAS-V]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Yescrypt