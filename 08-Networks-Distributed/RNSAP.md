---
title: "RNSAP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/RNSAP"
wikipedia_categories: ["Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# RNSAP

RNSAP (Radio Network Subsystem Application Part) is a 3GPP signalling protocol responsible for communications between RNCs Radio Network Controllers defined in 3GPP specification TS 25.423.  It is carried on the lur interface and provides functionality needed for soft handovers and SRNS (Serving Radio Network Subsystem) relocation (handoff between RNCs). It defines signalling between RNCs, including SRNC (Serving RNC) and DRNC (drift RNC).

     SRNC        |             DRNC
      |          IUR             |
    RNSAP        |             RNSAP
      |          |               |

Converge protol   |       Converge protol 

      |          |               |
   AAL 5         |             AAL5
    ATM          |             ATM

Physical links------→→→ Physical links
RNSAP Layer Architecture

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RNSAP