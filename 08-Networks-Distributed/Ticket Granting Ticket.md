---
title: "Ticket Granting Ticket"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Ticket_Granting_Ticket"
wikipedia_categories: ["Authentication protocols", "Computer access control protocols", "Computer network security", "Key management", "Key transport protocols"]
related: ["[[Kerberos (protocol)]]", "[[TACACS]]", "[[IEEE 802.1X]]", "[[Key distribution center]]", "[[NTLM]]", "[[Simultaneous Authentication of Equals]]", "[[Universal 2nd Factor]]", "[[Z-Wave]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]"]
---

# Ticket Granting Ticket

In some computer security systems, a Ticket Granting Ticket or Ticket to Get Tickets (TGT) is a small, encrypted identification file with a limited validity period. After authentication, this file is granted to a user for data traffic protection by the key distribution center (KDC) subsystem of authentication services such as Kerberos. The TGT file contains the session key, its expiration date, and the user's IP address, which protects the user from man-in-the-middle attacks.
The TGT is used to obtain a service ticket from Ticket Granting Service (TGS). User is granted access to network services only after this service ticket is provided.

## Related

- [[Kerberos (protocol)]]
- [[TACACS]]
- [[IEEE 802.1X]]
- [[Key distribution center]]
- [[NTLM]]
- [[Simultaneous Authentication of Equals]]
- [[Universal 2nd Factor]]
- [[Z-Wave]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ticket_Granting_Ticket