---
title: "Rdate"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Rdate"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Network time-related software", "Unix network-related software"]
related: ["[[Berkeley r-commands]]", "[[Finger (protocol)]]", "[[OFTP]]", "[[Portmap]]", "[[Rtelnet]]", "[[Telnet]]", "[[Wide Area Information Server]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]"]
---

# Rdate

On Unix-like operating systems, rdate is a tool for querying the current time from a network server and, optionally, setting the system time. Rdate uses the Time Protocol. The Time Protocol is generally considered obsolete and has been replaced by the Network Time Protocol (NTP). 
When used to set the local system time, rdate operates by changing system time immediately to the time and date returned by the server. Abrupt changes of clock settings have been found to cause problems for software relying on timing. This led to the development of the Network Time Protocol, which gradually changes the system time and does not skip ticks.
Due to the problems described above, rdate is generally used only on systems where NTP is not available, or in specialized circumstances where it is required that system time be set correctly as soon as possible during initial setup, before services which may be vulnerable to abrupt time-changes have started.

## Related

- [[Berkeley r-commands]]
- [[Finger (protocol)]]
- [[OFTP]]
- [[Portmap]]
- [[Rtelnet]]
- [[Telnet]]
- [[Wide Area Information Server]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rdate