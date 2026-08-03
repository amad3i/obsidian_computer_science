---
title: "Seccomp"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Seccomp"
wikipedia_categories: ["Computer security", "Cybersecurity engineering", "Linux kernel features"]
related: ["[[Biometric device]]", "[[Security of the Java software platform]]", "[[Trustworthy computing]]", "[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]"]
---

# Seccomp

seccomp (short for secure computing) is a computer security facility in the Linux kernel. seccomp allows a process to make a one-way transition into a "secure" state where it cannot make any system calls except exit(), sigreturn(), read() and write() to already-open file descriptors. Should it attempt any other system calls, the kernel will either just log the event or terminate the process with SIGKILL or SIGSYS. In this sense, it does not virtualize the system's resources but isolates the process from them entirely.
seccomp mode is enabled via the prctl(2) system call using the PR_SET_SECCOMP argument, or (since Linux kernel 3.17) via the seccomp(2) system call. seccomp mode used to be enabled by writing to a file, /proc/self/seccomp, but this method was removed in favor of prctl(). In some kernel versions, seccomp disables the RDTSC x86 instruction, which returns the number of elapsed processor cycles since power-on, used for high-precision timing.
seccomp-bpf is an extension to seccomp that allows filtering of system calls using a configurable policy implemented using Berkeley Packet Filter rules. It is used by OpenSSH and vsftpd as well as the Google Chrome/Chromium web browsers on ChromeOS and Linux. (In this regard seccomp-bpf achieves similar functionality, but with more flexibility and higher performance, to the older systrace—which seems to be no longer supported for Linux.)
Some consider seccomp comparable to OpenBSD pledge(2) and FreeBSD capsicum(4).

## Related

- [[Biometric device]]
- [[Security of the Java software platform]]
- [[Trustworthy computing]]
- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Seccomp