---
title: "HMAC-based one-time password"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/HMAC-based_one-time_password"
wikipedia_categories: ["Computer access control protocols", "Cryptographic algorithms", "Internet protocols"]
related: ["[[MS-CHAP]]", "[[OAuth]]", "[[RADIUS]]", "[[RadSec]]", "[[Time-based one-time password]]", "[[Universal 2nd Factor]]", "[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[B92 protocol]]", "[[Bach's algorithm]]"]
---

# HMAC-based one-time password

HMAC-based one-time password (HOTP) is a one-time password (OTP) algorithm based upon a hash-based message authentication code (HMAC). When a client attempts to access a server, a challenge is sent by the destination server to the client. The client then computes a response which represents a one time password. This often forms part of multi-factor authentication protocols such as the Open Authentication initiative (OATH) challenge-response algorithm.
HOTP was published as an informational IETF RFC 4226  in December 2005, documenting the algorithm along with a Java implementation. Since then, the algorithm has been adopted by many companies worldwide (see below). The HOTP algorithm is a freely available open standard.

## Related

- [[MS-CHAP]]
- [[OAuth]]
- [[RADIUS]]
- [[RadSec]]
- [[Time-based one-time password]]
- [[Universal 2nd Factor]]
- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[B92 protocol]]
- [[Bach's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HMAC-based_one-time_password