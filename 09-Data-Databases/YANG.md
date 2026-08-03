---
title: "YANG"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/YANG"
wikipedia_categories: ["Data modeling", "Data modeling languages", "Yet another"]
related: ["[[Cognition enhanced Natural language Information Analysis Method]]", "[[EXPRESS (data modeling language)]]", "[[Fundamental modeling concepts]]", "[[IDEF1X]]", "[[Object–role modeling]]", "[[QL]]", "[[Anchor modeling]]", "[[Apache Pig]]", "[[Armstrong's axioms]]", "[[Bernhard Thalheim]]"]
---

# YANG

Yet Another Next Generation (YANG, /jæŋ/) is a data modeling language for the definition of data sent over network management protocols such as the NETCONF and RESTCONF. Developed and maintained by the NETMOD working group in the Internet Engineering Task Force (IETF), YANG was initially published as RFC 6020 in October 2010, with a significant update to version 1.1 in August 2016 (RFC 7950).
YANG enables comprehensive network automation by providing a standardized way to model the configuration and state data of network elements. The language can be used to define the format of event notifications emitted by network devices and allows data modelers to define the signature of RPCs that can be invoked on network elements via the NETCONF protocol. Being protocol-independent, YANG models can be converted into various encoding formats, including XML, JSON, and CBOR, depending on the network configuration protocol's support.
YANG is a modular language and represents data structures in a hierarchical tree format. It includes numerous built-in data types, with the capability for users to derive additional application-specific types. More complex reusable data structures can be represented as "groupings," which promote model reusability and consistency. YANG data models can use XPath expressions to define constraints on the elements of a YANG data model, enabling validation of configuration data before it is committed to devices.
YANG has become the de facto standard for modeling network device configurations across the telecommunications industry and is widely supported by major network equipment manufacturers. It plays a crucial role in software-defined networking (SDN) and network function virtualization (NFV) environments by providing a consistent interface for programmatic network management.

## Related

- [[Cognition enhanced Natural language Information Analysis Method]]
- [[EXPRESS (data modeling language)]]
- [[Fundamental modeling concepts]]
- [[IDEF1X]]
- [[Object–role modeling]]
- [[QL]]
- [[Anchor modeling]]
- [[Apache Pig]]
- [[Armstrong's axioms]]
- [[Bernhard Thalheim]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/YANG