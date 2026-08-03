---
title: "Group identifier"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Group_identifier"
wikipedia_categories: ["Unix", "Unix file system technology"]
related: ["[[User identifier]]", "[[-dev-full]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Boot folder]]", "[[Everything is a file]]", "[[Gecos field]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Ldconfig]]"]
---

# Group identifier

In Unix-like systems, multiple users can be put into groups. POSIX and conventional Unix file system permissions are organized into three classes, user, group, and others. The use of groups allows additional abilities to be delegated in an organized fashion, such as access to disks, printers, and other peripherals. This method, among others, also enables the superuser to delegate some administrative tasks to normal users, similar to the Administrators group on Microsoft Windows NT and its derivatives.
A group identifier, often abbreviated to GID, is a numeric value used to represent a specific group. The range of values for a GID varies amongst different systems; at the very least, a GID can be between 0 and 32,767, with one restriction: the login group for the superuser must have GID 0. This numeric value is used to refer to groups in the /etc/passwd and /etc/group files or their equivalents. Shadow password files and Network Information Service also refer to numeric GIDs. The group identifier is a necessary component of Unix file systems and processes.

## Related

- [[User identifier]]
- [[-dev-full]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Boot folder]]
- [[Everything is a file]]
- [[Gecos field]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Ldconfig]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Group_identifier