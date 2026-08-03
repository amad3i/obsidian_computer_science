---
title: "/dev/full"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki//dev/full"
wikipedia_categories: ["Device file", "Linux stubs", "Software testing", "Unix file system technology"]
related: ["[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]", "[[Application performance engineering]]"]
---

# /dev/full

In Linux, FreeBSD, and NetBSD, /dev/full, or the always-full device, is a special file that always returns the error code ENOSPC (meaning "No space left on device") on writing, and provides any number of zero bytes to a process that reads from it (similar to /dev/zero). This device is usually used when testing the behavior of a program when it encounters a "disk full" error.

## Related

- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]
- [[All-pairs testing]]
- [[Analytical Performance Modeling]]
- [[API testing]]
- [[Application performance engineering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki//dev/full