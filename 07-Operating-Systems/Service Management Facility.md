---
title: "Service Management Facility"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Service_Management_Facility"
wikipedia_categories: ["Process (computing)", "Sun Microsystems software", "Unix process- and task-management-related software"]
related: ["[[Kill (command)]]", "[[SystemStarter]]", "[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]", "[[Coprocess]]"]
---

# Service Management Facility

Service Management Facility (SMF) is a feature of the Solaris operating system as of version 10 and OpenSolaris-descendant illumos with its illumos distributions, that creates a supported, unified model for services and service management on each Solaris or illumos system and replaces init.d scripts. SMF introduces:

Dependency order.  Services sometimes depend on one another for proper operation, and a robust system should know each service's dependencies.  If an underlying service fails, it needs to be corrected before other services that depend upon it are affected.
Configurable boot verbosity
Delegation of tasks to non-root users.  A service can be configured to run within a limited set of privileges, rather than as the all-powerful root user.  If a service has been compromised, the amount of damage that can be inflicted by the intruder will be minimized if the service's power is constrained to that of a more limited user.
Parallel starting of services.  This speeds up the boot process by starting multiple services simultaneously, allowing idle CPU time resulting from a service that is temporarily blocked to be relinquished for use by other services that can start independently of the blocked service.
Automatic service restart after failure.  Works in conjunction with the Solaris Fault Manager, allowing software recovery in the event of hardware faults (CPU, memory), admin error such as accidental kills, and software core dumps.
All these capabilities are made possible by treating Services as "first class objects".  That is, they are more than just user-executed software to the OS.  They can be defined to have special states that allow finer control and permit monitoring and probing for diagnosing software failures, rather than having the administrator or dedicated "restarter" modules kill and restart the service as before.

## Related

- [[Kill (command)]]
- [[SystemStarter]]
- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Context switch]]
- [[Coprocess]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Service_Management_Facility