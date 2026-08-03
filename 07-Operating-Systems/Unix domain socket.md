---
title: "Unix domain socket"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Unix_domain_socket"
wikipedia_categories: ["Network socket", "Unix"]
related: ["[[ACM SIGOPS Annual Technical Conference]]", "[[Circuit-level gateway]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]", "[[Ioctl]]", "[[Job control (Unix)]]", "[[Ldconfig]]", "[[Line discipline]]", "[[Line Printer Daemon protocol]]"]
---

# Unix domain socket

A Unix domain socket (UDS), also called a local socket or inter-process communication (IPC) socket, is a communication endpoint used for data exchange between processes running on the same Unix or Unix-like operating system.
The term Unix domain socket refers to the domain argument value AF_UNIX passed to the system call that creates the socket. The same communication domain can also be selected with AF_LOCAL.
Valid type argument values for a UDS are:

SOCK_STREAM (compare to TCP) – a stream-oriented socket
SOCK_DGRAM (compare to UDP) – a datagram-oriented socket that preserves message boundaries; on most Unix implementations, Unix domain datagram sockets are reliable and do not reorder datagrams
SOCK_SEQPACKET (compare to SCTP) – a connection-oriented sequenced-packet socket that preserves message boundaries and delivers messages in the order sent
The UDS facility is a standard component of a POSIX operating system.
The API for a UDS is similar to that of an Internet socket, but instead of using an underlying network protocol, communication takes place entirely within the operating system kernel. A UDS may use the file system as its address namespace. Some operating systems, such as Linux, provide additional namespaces. Processes refer to a UDS through a file system inode, allowing two processes to communicate by opening the same socket.
In addition to sending data, processes can pass file descriptors over a UDS connection by using the sendmsg() and recvmsg() system calls. This allows one process to grant another process access to a file descriptor that it would not otherwise be able to use. This can be used to implement a rudimentary form of capability-based security.

## Related

- [[ACM SIGOPS Annual Technical Conference]]
- [[Circuit-level gateway]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]
- [[Ioctl]]
- [[Job control (Unix)]]
- [[Ldconfig]]
- [[Line discipline]]
- [[Line Printer Daemon protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Unix_domain_socket