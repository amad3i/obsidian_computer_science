---
title: "Mental poker"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Mental_poker"
wikipedia_categories: ["Cryptographic algorithms"]
related: ["[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Block cipher mode of operation]]", "[[CDMF]]", "[[Ciphertext stealing]]", "[[Common Scrambling Algorithm]]", "[[CryptGenRandom]]", "[[Crypto++]]"]
---

# Mental poker

Mental poker is the common name for a set of cryptographic problems that concerns playing a fair game over distance without the need for a trusted third party. The term is also applied to the theories surrounding these problems and their possible solutions. The name comes from the card game poker which is one of the games to which this kind of problem applies. Similar problems described as two party games are Blum's flipping a coin over a distance,  Yao's Millionaires' Problem, and Rabin's oblivious transfer.
The problem can be described thus: "How can one allow only authorized actors to have access to certain information while not using a trusted arbiter?" (Eliminating the trusted third-party avoids the problem of trying to determine whether the third party can be trusted or not, and may also reduce the resources required.)
In poker, this could translate to: "How can we make sure no player is stacking the deck or peeking at other players' cards when we are shuffling the deck ourselves?". In a physical card game, this would be relatively simple if the players were sitting face to face and observing each other, at least if the possibility of conventional cheating can be ruled out. However, if the players are not sitting at the same location but instead are at widely separate locations and pass the entire deck between them (using the postal mail, for instance), this suddenly becomes very difficult. And for electronic card games, such as online poker, where the mechanics of the game are hidden from the user, this is impossible unless the method used is such that it cannot allow any party to cheat by manipulating or inappropriately observing the electronic "deck".
Several protocols for doing this have been suggested, the first by Adi Shamir, Ron Rivest and Len Adleman (the creators of the RSA-encryption protocol). This protocol was the first example of two parties conducting secure computation rather than secure message transmission, employing cryptography; later on due to leaking partial information in the original protocol, this led to the definition of semantic security by Shafi Goldwasser and Silvio Micali. The concept of multi-player mental poker was introduced in Moti Yung's 1984 book Cryptoprotocols. The area has later evolved into what is known as secure multi-party computation protocols (for two parties, and multi parties as well).

## Related

- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Block cipher mode of operation]]
- [[CDMF]]
- [[Ciphertext stealing]]
- [[Common Scrambling Algorithm]]
- [[CryptGenRandom]]
- [[Crypto++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mental_poker