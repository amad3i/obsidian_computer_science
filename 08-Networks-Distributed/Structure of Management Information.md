---
title: "Structure of Management Information"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Structure_of_Management_Information"
wikipedia_categories: ["ASN.1", "Computing stubs", "Data modeling", "Network management"]
related: ["[[Tuple-versioning]]", "[[Anchor modeling]]", "[[Armstrong's axioms]]", "[[Auditory display]]", "[[Automatic system recovery]]", "[[Autoscaling]]", "[[Availability zone]]", "[[Bernhard Thalheim]]", "[[Bidirectional Forwarding Detection]]", "[[BIM Collaboration Format]]"]
---

# Structure of Management Information

In computing, the Structure of Management Information (SMI), an adapted subset of ASN.1, is a technical language used in definitions of Simple Network Management Protocol (SNMP) and its extensions to define sets ("modules") of related managed objects in a Management Information Base (MIB).
SMI subdivides into three parts:  module definitions, object definitions, and notification definitions.

Module definitions are used when describing information modules. An ASN.1 macro, MODULE-IDENTITY, is used to concisely convey the semantics of an information module.
Object definitions describe managed objects.  An ASN.1 macro, OBJECT-TYPE, is used to concisely convey the syntax and semantics of a managed object.
Notification definitions (aka "traps") are used when describing unsolicited transmissions of management information.  An ASN.1 macro, NOTIFICATION-TYPE, concisely conveys the syntax and semantics of a notification.

## Related

- [[Tuple-versioning]]
- [[Anchor modeling]]
- [[Armstrong's axioms]]
- [[Auditory display]]
- [[Automatic system recovery]]
- [[Autoscaling]]
- [[Availability zone]]
- [[Bernhard Thalheim]]
- [[Bidirectional Forwarding Detection]]
- [[BIM Collaboration Format]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Structure_of_Management_Information