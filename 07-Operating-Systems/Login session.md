---
title: "Login session"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Login_session"
wikipedia_categories: ["Operating system stubs", "Operating system technology"]
related: ["[[CPU shielding]]", "[[Flag (programming)]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Blocking (computing)]]", "[[Busdma]]"]
---

# Login session

In computing, a login session is the period of activity between a user logging in and logging out of a (multi-user) system.
On Unix and Unix-like operating systems, a login session takes one of two main forms:

When a textual user interface is used, a login session is represented as a kernel session — a collection of process groups with the logout action managed by a session leader.
Where an X display manager is employed, a login session is considered to be the lifetime of a designated user process that the display manager invokes.
On Windows NT-based systems, login sessions are maintained by the kernel and control of them is overseen by the Local Security Authority Subsystem Service (LSA). winlogon responds to the secure attention key, it requests the LSA to create login sessions on login, and terminates all of the processes belonging to a login session on logout.

## Related

- [[CPU shielding]]
- [[Flag (programming)]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Blocking (computing)]]
- [[Busdma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Login_session