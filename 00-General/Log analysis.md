---
title: "Log analysis"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Log_analysis"
wikipedia_categories: ["Computer systems", "Web log analysis software"]
related: ["[[3D Content Retrieval]]", "[[Aladdin (BlackRock)]]", "[[Alert correlation]]", "[[Altos 586]]", "[[Automotive navigation system]]", "[[Computer bureau]]", "[[Computer-aided maintenance]]", "[[Continuous availability]]", "[[Convergence research]]", "[[Cyber manufacturing]]"]
---

# Log analysis

In computer log management and intelligence, log analysis (or system and network log analysis) is an art and science seeking to make sense of computer-generated records (also called log or audit trail records). The process of creating such records is called data logging.
Typical reasons why people perform log analysis are:

Compliance with security policies
Compliance with audit or regulation
System troubleshooting
Forensics (during investigations or in response to a subpoena)
Security incident response
Understanding online user behavior
Logs are emitted by network devices, operating systems, applications and all manner of intelligent or programmable devices. A stream of messages in time sequence often comprises a log. Logs may be directed to files and stored on disk or directed as a network stream to a log collector.
Log messages must usually be interpreted concerning the internal state of its source (e.g., application) and announce security-relevant or operations-relevant events (e.g., a user login, or a systems error).
Logs are often created by software developers to aid in the debugging of the operation of an application or understanding how users are interacting with a system, such as a search engine. The syntax and semantics of data within log messages are usually application or vendor-specific. The terminology may also vary; for example, the authentication of a user to an application may be described as a log in, a logon, a user connection or an authentication event. Hence, log analysis must interpret messages within the context of an application, vendor, system or configuration to make useful comparisons to messages from different log sources.
Log message format or content may not always be fully documented. A task of the log analyst is to induce the system to emit the full range of messages to understand the complete domain from which the messages must be interpreted.
A log analyst may map varying terminology from different log sources into a uniform, normalized terminology so that reports and statistics can be derived from a heterogeneous environment. For example, log messages from Windows, Unix, network firewalls, and databases may be aggregated into a "normalized" report for the auditor.  Different systems may signal different message priorities with a different vocabulary, such as "error" and "warning" vs. "err", "warn", and "critical".
Hence, log analysis practices exist on the continuum from text retrieval to reverse engineering of software.

## Related

- [[3D Content Retrieval]]
- [[Aladdin (BlackRock)]]
- [[Alert correlation]]
- [[Altos 586]]
- [[Automotive navigation system]]
- [[Computer bureau]]
- [[Computer-aided maintenance]]
- [[Continuous availability]]
- [[Convergence research]]
- [[Cyber manufacturing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Log_analysis