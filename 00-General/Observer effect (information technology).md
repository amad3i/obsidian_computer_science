---
title: "Observer effect (information technology)"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Observer_effect_(information_technology)"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Observer effect (information technology)

In information technology, the observer effect is the impact on the behaviour of a computer process caused by the act of observing the process while it is running.
For example: if a process uses a log file to record its progress, the process could slow down. Furthermore, the act of viewing the file while the process is running could cause an I/O error in the process, which could, in turn, cause it to stop. Another example would be observing the performance of a CPU by running both the observed and observing programs on the same CPU, which will lead to inaccurate results because the observer program itself affects the CPU performance (modern, heavily cached and pipelined CPUs are particularly affected by this kind of observation).
The observer effect could either have a positive or negative impact on the computer process behaviour. A positive impact can be software bugs, also known as Heisenbugs, which diminish or change their negative behavior when observation mechanisms, such as debugging, are enabled. Such bugs usually create extra difficulties in being isolated.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]
- [[Codecademy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Observer_effect_(information_technology)