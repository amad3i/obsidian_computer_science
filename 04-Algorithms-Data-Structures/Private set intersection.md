---
title: "Private set intersection"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Private_set_intersection"
wikipedia_categories: ["Cryptography", "Cryptography stubs", "Hashing"]
related: ["[[Batch cryptography]]", "[[Branch number]]", "[[Cipher device]]", "[[Ciphertext expansion]]", "[[Client-side encryption]]", "[[Codress message]]", "[[Completeness (cryptography)]]", "[[Conjugate coding]]", "[[Correlation immunity]]", "[[Cover (telecommunications)]]"]
---

# Private set intersection

Private set intersection is a secure multiparty computation cryptographic technique that allows two parties holding sets to compare encrypted versions of these sets in order to compute the intersection. In this scenario, neither party reveals anything to the counterparty except for the elements in the intersection.

Other variants of this exist, such as the server-client scenario, in which only the client learns the intersection of her set with the set of the server, without the server learning intersection of his set with the clients.

For the comparison of data sets by cryptographic hashes on a small or predictable domain, precautions should be taken to prevent dictionary attacks.
Apple uses this technique in Password Monitoring. It has proposed using the technology for its announced Expanded Protections for Children 
In general, PSI protocols can be categorized into two broad categories: (1) traditional PSI and (2) delegated PSI. In the traditional PSI category, the data owners interact directly with each other and need to have a copy of their set at the time of the computation, e.g.,. In the delegated PSI the computation of PSI and/or the storage of sets can be delegated to a third-party server (that is itself might be a passive or active adversary). The delegated PSI category can be further divided into two classes: (a) those that support one-off delegation, and (b) those that support repeated delegation. The PSI protocols that support one-off delegation require the data owner to re-encode its data and send the encoded data to the server for each computation, e.g.,. Those that support repeated delegation allow the data owners to upload their (encrypted) data to the server only once, and then re-use it many times for each computation carried out but the server, e.g.,
Recently, researchers have proposed a variant of PSI protocol (in both traditional and delegated categories) that support data update, e.g., . This type of PSI protocol lets data owners insert/delete set elements into/from their data with low overheads and in a privacy-preserving manner.

## Related

- [[Batch cryptography]]
- [[Branch number]]
- [[Cipher device]]
- [[Ciphertext expansion]]
- [[Client-side encryption]]
- [[Codress message]]
- [[Completeness (cryptography)]]
- [[Conjugate coding]]
- [[Correlation immunity]]
- [[Cover (telecommunications)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Private_set_intersection