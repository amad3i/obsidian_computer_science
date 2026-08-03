---
title: "Bcrypt"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bcrypt"
wikipedia_categories: ["Cryptographic hash functions", "Cryptographic software", "Key derivation functions"]
related: ["[[Argon2]]", "[[Crypt (C)]]", "[[Scrypt]]", "[[Yescrypt]]", "[[Ascon (cipher)]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]", "[[Crypto++]]", "[[Cryptographic hash function]]", "[[Cryptol]]"]
---

# Bcrypt

bcrypt is a password-hashing function designed by Niels Provos and David Mazières. It is based on the Blowfish cipher and presented at USENIX in 1999. Besides incorporating a salt to protect against rainbow table attacks, bcrypt is an adaptive function: over time, the iteration count can be increased to make it slower, so it remains resistant to brute-force search attacks even with increasing computation power.
The bcrypt function is the default password hash algorithm for OpenBSD, and was the default for some Linux distributions such as SUSE Linux.
There are implementations of bcrypt in C, C++, C#, Embarcadero Delphi, Elixir, Go, Java, JavaScript, Perl, PHP, Ruby, Python, Rust, V (Vlang), Zig and other languages.

## Related

- [[Argon2]]
- [[Crypt (C)]]
- [[Scrypt]]
- [[Yescrypt]]
- [[Ascon (cipher)]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]
- [[Crypto++]]
- [[Cryptographic hash function]]
- [[Cryptol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bcrypt