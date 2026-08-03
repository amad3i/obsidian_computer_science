---
title: "Opportunistic Wireless Encryption"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Opportunistic_Wireless_Encryption"
wikipedia_categories: ["Internet privacy"]
related: ["[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]", "[[2023 Bangladesh Government website data breach]]", "[[Anonymous blog]]", "[[Behavioral retargeting]]", "[[Big data ethics]]", "[[Canvas fingerprinting]]", "[[Click analytics]]", "[[Client Hints]]"]
---

# Opportunistic Wireless Encryption

Opportunistic Wireless Encryption (OWE) is a Wi-Fi standard which ensures that communication between a public hotspot and end devices is protected from other end devices. In contrast to conventional public hotspots, the data is transmitted in encrypted form. OWE was introduced by the Wi-Fi Alliance in 2018 as part of the Wi-Fi Certified Enhanced Open program.
OWE is an extension to IEEE 802.11. It is an encryption technique similar to that of Simultaneous Authentication of Equals (SAE) and is specified by Internet Engineering Task Force (IETF) in RFC 8110 with devices certified as Wi-Fi Certified Enhanced Open by the Wi-Fi Alliance.
With a network without a password, each WPA3 device that connects to it will still have its connection encrypted. OWE does encryption, not authentication; evil twin attack protection requires either WPA3-Personal or WPA3-Enterprise.
Unlike conventional Wi-Fi, it provides "Individualized Data Protection" such that data traffic between a client and access point is "individualized." Other clients can still sniff and record this traffic, but they can't decrypt it.

"OWE is a means of adding encryption to open networks...OWE only protects against passive attacks."
Opportunistic Wireless Encryption is a Wi-Fi Enhanced Open authentication mode, as a part of Wi-Fi Protected Access 3. OWE performs an unauthenticated Diffie–Hellman (DH) key exchange at association time.
For the wireless client to know the WLAN supports OWE, it must receive a Probe Response from the wireless access point in response to its Probe Request. OWE still uses 802.11 Open System Authentication, then the Elliptic Curve Diffie-Hellman Ephemeral exchange occurs in the Association process.  After Association is successful the 4-way handshake can occur, and from then on data frames are encrypted.

## Related

- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]
- [[2023 Bangladesh Government website data breach]]
- [[Anonymous blog]]
- [[Behavioral retargeting]]
- [[Big data ethics]]
- [[Canvas fingerprinting]]
- [[Click analytics]]
- [[Client Hints]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Opportunistic_Wireless_Encryption