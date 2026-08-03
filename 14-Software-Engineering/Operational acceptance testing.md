---
title: "Operational acceptance testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Operational_acceptance_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Operational acceptance testing

Operational acceptance testing (OAT) is  used to conduct operational readiness (pre-release) of a product, service, or system as part of a quality management system. OAT is a common type of non-functional software testing, used mainly in software development and software maintenance projects. This type of testing focuses on the operational readiness of the system to be supported, and/or to become part of the production environment. Hence, it is also known as operational readiness testing (ORT) or operations readiness and assurance testing (OR&A). Functional testing within OAT is limited to those tests which are required to verify the non-functional aspects of the system.
OAT elaborates upon and compartmentalises operational aspects of acceptance testing.
According to the International Software Testing Qualifications Board (ISTQB), OAT may include checking the backup/restore facilities, IT disaster recovery procedures, maintenance tasks and periodic check of security vulnerabilities., and whitepapers on ISO 29119 and Operational Acceptance by Anthony Woods, and ISO 25000 and Operational Acceptance Testing by Dirk Dach et al., OAT generally includes:

Component Testing
Failover (Within the same data centre)
Component fail-over
Network fail-over
Functional Stability
Accessibility
Conversion
Stability
Usability
IT Service Management (Supportability)
Monitoring and Alerts (to ensure proper alerts are configured in the system if something goes wrong)
Portability
Compatibility
Interoperability
Installation and Backout
Localization
Recovery (across data centres)
Application/system recovery
Data recovery
Reliability
Backup and Restoration (Recovery)
Disaster Recovery
Maintainability
Performance, Stress and Volume,
Procedures (Operability) and Supporting Documentation (Supportability)
Security and Penetration
During OAT changes may be made to environmental parameters which the application uses to run smoothly. For example, with Microsoft Windows applications with a mixed or hybrid architecture, this may include: Windows services, configuration files, web services, XML files, COM+ components, web services, IIS, stored procedures in databases, etc. Typically OAT should occur after each main phase of the development life cycle: design, build, and functional testing. In sequential projects it is often viewed as a final verification before a system is released; where in agile and iterative projects, a more frequent execution of OAT occurs providing stakeholders with assurance of continued stability of the system and its operating environment.
An approach used in OAT may follow these steps:

Design the system,
Assess the design,
Build the system,
Confirm if built to design,
Evaluate the system addresses business functional requirements,
Assess the system for compliance with non-functional requirements,
Deploy the system,
Assess operability and supportability of the system.
For running the OAT test cases, the tester normally has exclusive access to the system or environment. This means that a single tester would be executing the test cases at a single point of time. For OAT the exact Operational Readiness quality gates are defined: both entry and exit gates. The primary emphasis of OAT should be on the operational stability, portability and reliability of the system.

## Related

- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]
- [[All-pairs testing]]
- [[Analytical Performance Modeling]]
- [[API testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Operational_acceptance_testing