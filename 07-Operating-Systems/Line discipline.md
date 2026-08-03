---
title: "Line discipline"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Line_discipline"
wikipedia_categories: ["Computer terminals", "Unix", "Unix stubs"]
related: ["[[Message of the day]]", "[[Qsub]]", "[[Spl (Unix)]]", "[[Symlink race]]", "[[Terminal mode]]", "[[Utmp]]", "[[Words (Unix)]]", "[[ACM SIGOPS Annual Technical Conference]]", "[[Busdma]]", "[[Computer terminal]]"]
---

# Line discipline

A line discipline (LDISC) is a layer in the terminal subsystem in Unix-like systems since Version 7 Unix. The terminal subsystem consists of three layers: the upper layer to provide the character device interface, the lower hardware driver to communicate with the hardware or pseudo terminal, and the middle line discipline to implement behavior common to terminal devices.
The line discipline glues the low level device driver code with the high level generic interface routines (such as read(2), write(2) and ioctl(2)), and is responsible for implementing the semantics associated with the device. The policy is separated from the device driver so that the same serial hardware driver can be used by devices that require different data handling.
For example, the standard line discipline processes the data it receives from the hardware driver and from applications writing to the device according to the requirements of a terminal on a Unix-like system. On input, it handles special characters such as the interrupt character (typically Control-C) and the erase and kill characters (typically backspace or delete, and Control-U, respectively) and, on output, it replaces all the LF characters with a CR/LF sequence.
A serial port could also be used for a dial-up Internet connection using a serial modem and PPP.  In this case, a PPP line discipline would be used; it would accumulate input data from the serial line into PPP input packets, delivering them to the networking stack rather than to the character device, and would transmit packets delivered to it by the networking stack on the serial line.
Some Unix-like systems, such as Solaris, use STREAMS to implement line disciplines.

## Related

- [[Message of the day]]
- [[Qsub]]
- [[Spl (Unix)]]
- [[Symlink race]]
- [[Terminal mode]]
- [[Utmp]]
- [[Words (Unix)]]
- [[ACM SIGOPS Annual Technical Conference]]
- [[Busdma]]
- [[Computer terminal]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Line_discipline