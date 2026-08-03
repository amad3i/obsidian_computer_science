---
title: "Crash-only software"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Crash-only_software"
wikipedia_categories: ["Operating system technology", "Software engineering stubs"]
related: ["[[Active reviews for intermediate designs]]", "[[Adaptive algorithm]]", "[[ALTQ]]", "[[Ambiguous viewpoint]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Augmented reality-based testing]]", "[[Basis path testing]]"]
---

# Crash-only software

A crash-only software is a computer program that handle failures by simply restarting, without attempting any sophisticated recovery.  Correctly written components of crash-only software can microreboot to a known-good state without the help of a user. A related recovery technique is the microreboot, which restarts only a faulty fine-grained component rather than rebooting the whole application or server; in an Internet auction application, Candea et al. reported that microreboots recovered most of the same failures as full reboots while reducing recovery time and lost work by about an order of magnitude. Since failure-handling and normal startup use the same methods, this can increase the chance that bugs in failure-handling code will be noticed, except when there are leftover artifacts, such as data corruption from a severe failure, that don't occur during normal startup.
Crash-only software also has benefits for end-users. All too often, applications do not save their data and settings while running, only at the end of their use. For example, word processors usually save settings when they are closed. A crash-only application is designed to save all changed user settings soon after they are changed, so that the persistent state matches that of the running machine. No matter how an application terminates (be it a clean close or the sudden failure of a laptop battery), the state will persist.

## Related

- [[Active reviews for intermediate designs]]
- [[Adaptive algorithm]]
- [[ALTQ]]
- [[Ambiguous viewpoint]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Augmented reality-based testing]]
- [[Basis path testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Crash-only_software