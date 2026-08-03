---
title: "High Level Architecture"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/High_Level_Architecture"
wikipedia_categories: ["Distributed computing architecture", "IEEE standards", "Military simulation", "Simulation software"]
related: ["[[Distributed Interactive Simulation]]", "[[RPR FOM]]", "[[Aggregate Level Simulation Protocol]]", "[[Pointman (user interface)]]", "[[Adaptive sampling]]", "[[Advanced disaster management simulator]]", "[[Aerospike (database)]]", "[[AgentSheets]]", "[[Altibase]]", "[[Amoeba (operating system)]]"]
---

# High Level Architecture

The High Level Architecture (HLA) is a standard for distributed simulation, used when building a simulation for a larger purpose by combining (federating) several simulations. The standard was developed in the mid-1990s under the leadership of the US Department of Defense in partnership with the Defense Advanced Research Projects Agency (DARPA) and was later transitioned to the Defense Modeling and Simulation Office (DMSO) where it later become an open international IEEE standard. It is a recommended standard within NATO through STANAG 4603. Today the HLA is used in a number of domains including defense and security and civilian applications.
The purpose of HLA is to enable interoperability and reuse. Key properties of HLA are:

The ability to connect simulations running on different computers, locally or widely distributed, independent of their operating system and implementation language, into one Federation.
Ability to specify and use information exchange data models, Federation Object Models (FOMs), for different application domains.
Services for exchanging information using a publish-subscribe mechanism, based on the FOM, and with additional filtering options.
Services for coordinating logical (simulation) time and time-stamped data exchange.
Management services for inspecting and adjusting the state of a Federation.
HLA forms the basis for developing standardized and extendable FOMs in different communities, for example in aerospace and defense.
The architecture specifies the following components.

A Run-time Infrastructure (RTI) that provides a standardized set of services through different programming languages. These services include information exchange, synchronization and federation management
Federates that are individual simulation systems using RTI services.
A Federation Object Model (FOM) that specifies the Object Classes and Interaction Classes used to exchange data. The FOM can describe information for any domain.
Together the above components form a Federation.
The HLA standard consists of three parts:

IEEE Std 1516-2025 Framework and Rules, which specifies ten architectural rules that the components or the entire federation shall adhere to.
IEEE Std 1516.1-2025 Federate Interface Specification, which specifies the services that shall be provided by the RTI. The services are provided as C++ and Java APIs as well as Web Services.
IEEE Std 1516.2-2025 Object Model Template Specification, which specifies the format that HLA object models, such as the FOM, shall use.

## Related

- [[Distributed Interactive Simulation]]
- [[RPR FOM]]
- [[Aggregate Level Simulation Protocol]]
- [[Pointman (user interface)]]
- [[Adaptive sampling]]
- [[Advanced disaster management simulator]]
- [[Aerospike (database)]]
- [[AgentSheets]]
- [[Altibase]]
- [[Amoeba (operating system)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/High_Level_Architecture