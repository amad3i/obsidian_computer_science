---
title: "Loop-switch sequence"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Loop-switch_sequence"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Loop-switch sequence

A loop-switch sequence (also known as the for-case paradigm or Anti-Duff's Device) is a programming antipattern where a clear set of steps is implemented as a switch-within-a-loop. The loop-switch sequence is a specific derivative of spaghetti code.
It is not necessarily an antipattern to use a switch statement within a loop—it is only considered incorrect when used to model a known sequence of steps.  The most common example of the correct use of a switch within a loop is an inversion of control such as an event handler.  In event handler loops, the sequence of events is not known at compile-time, so the repeated switch is both necessary and correct (see event-driven programming, event loop and event-driven finite state machine).
This is not a performance antipattern, though it may lead to an inconsequential performance penalty due to the lack of an unrolled loop. Rather, it is a clarity antipattern, as in any non-trivial example it is much more difficult to decipher the intent and actual function of the code than the more straightforward refactored solution.

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

- Wikipedia: https://en.wikipedia.org/wiki/Loop-switch_sequence