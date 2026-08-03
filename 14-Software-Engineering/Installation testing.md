---
title: "Installation testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Installation_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Installation testing

Installation testing is a type of software testing that verifies that users can successfully install and set up software in its intended environments (e.g., operating systems, computer hardware). Most software systems have installation procedures that are needed before they can be used for their main purpose. Installation testing focuses on these procedures and whether they're sufficient for achieving an installed, usable software system. Procedures of this kind may involve full or partial upgrades, and install/uninstall processes.
As a software quality assurance and software testing tactic, installation testing may look for errors that occur in the installation process that affect the user's perception and capability to use the installed software. There are many events that may affect the software installation, and installation testing may test for proper installation while checking for associated activities, events, and artifacts. Some examples include the following:

A user must select a variety of options.
Dependent files and libraries must be allocated, loaded or located.
Valid hardware configurations must be present.
Software systems may need connectivity to connect to other software systems.
Valid, accurate, and sufficient documentation (e.g., installation guide, user manual, quick reference, README file, etc.) must be present and accessible.
Installation testing may also be considered an activity-based testing approach. For example, the tester can install the software in various ways and on various types of compatible systems, check which files have been added or changed in the process, and verify that the installed software works as intended. The tester can then check what happens when the software is uninstalled.
This testing is typically performed in Operational acceptance testing, by a software testing engineer in conjunction with the configuration manager. Implementation testing is usually defined as testing which places a compiled version of code into the testing or pre-production environment, from which it may or may not progress into production.unclear reference to implementation testing, This generally takes place outside of the software development environment to limit code corruption from other future or past releases (or from the use of the wrong version of dependencies such as shared libraries) which may reside on the development environment.unclear connection to implementation testing and software development environment,
The simplest installation approach is to run an install program, sometimes called package software.  This package software typically uses a setup program which acts as a multi-configuration wrapper and which may allow the software to be installed on a variety of machine and/or operating environments. Every possible configuration should receive an appropriate level of testing so that it can be released to customers with confidence.
In distributed systems, particularly where software is to be released into an already live target environment (such as an operational website) installation (or software deployment as it is sometimes called) can involve database schema changes as well as the installation of new software. Deployment plans in such circumstances may include back-out procedures whose use is intended to roll the target environment back if the deployment is unsuccessful. Ideally, the deployment plan itself should be tested in an environment that is a replica of the live environment. A factor that can increase the organizational requirements of such an exercise is the need to synchronize the data in the test deployment environment with that in the live environment with minimum disruption to live operation. This type of implementation may include testing of the processes which take place during the installation or upgrade of a multi-tier application. This type of testing is commonly compared to a dress rehearsal or may even be called a "dry run".

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

- Wikipedia: https://en.wikipedia.org/wiki/Installation_testing