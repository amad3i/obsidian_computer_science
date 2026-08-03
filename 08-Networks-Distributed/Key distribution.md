---
title: "Key distribution"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Key_distribution"
wikipedia_categories: ["Cloud computing", "Key management"]
related: ["[[Abiquo Enterprise Edition]]", "[[AI data center]]", "[[AI infrastructure]]", "[[Alibaba Cloud]]", "[[Amaryllo]]", "[[Amazon Elastic Compute Cloud]]", "[[Amazon Kinesis]]", "[[Ampere Computing]]", "[[Apache CarbonData]]", "[[Apache Drill]]"]
---

# Key distribution

In symmetric key cryptography, both parties must possess a secret key which they must exchange prior to using any encryption.  Distribution of secret keys has been problematic until recently, because it involved face-to-face meeting, use of a trusted courier, or sending the key through an existing encryption channel.  The first two are often impractical and unsafe, while the third depends on the security of a previous key exchange.
In public key cryptography, the key distribution of public keys is done through public key servers. When a person creates a key-pair, they keep one key private and the other, known as the public-key, is uploaded to a server where it can be accessed by anyone to send the user a private, encrypted, message.
Secure Sockets Layer (SSL) uses Diffie–Hellman key exchange if the client does not have a public-private key pair and a published certificate in the public key infrastructure, and Public Key Cryptography if the user does have both the keys and the credential.
Key distribution is an important issue in wireless sensor network (WSN) design. There are many key distribution schemes in the literature that are designed to maintain an easy and at the same time secure communication among sensor nodes. The most accepted method of key distribution in WSNs is key predistribution, where secret keys are placed in sensor nodes before deployment. When the nodes are deployed over the target area, the secret keys are used to create the network.
For more info see: key distribution in wireless sensor networks.

## Related

- [[Abiquo Enterprise Edition]]
- [[AI data center]]
- [[AI infrastructure]]
- [[Alibaba Cloud]]
- [[Amaryllo]]
- [[Amazon Elastic Compute Cloud]]
- [[Amazon Kinesis]]
- [[Ampere Computing]]
- [[Apache CarbonData]]
- [[Apache Drill]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Key_distribution