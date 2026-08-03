---
title: "Neutral build"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Neutral_build"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Neutral build

In software development, a neutral build is a software build that reflects the current state of the source code checked into the source code version control system by the developers, and done in a neutral environment (an environment not used for development).
A nightly build is a neutral build that takes place automatically. These typically take place when no one is likely to be working in the office so that there are no changes to the source code during the build. The results of the build are inspected by the arriving programmers, who generally place a priority on ensuring the recent changes to the source code have not broken the build process or functionality of the software. Nightly builds also ensure that the build tools have not broken due to system updates, and are therefore often run whether any source code has changed or not.
In contrast, continuous integration environments automatically rebuild the project whenever changes are checked in – often several times a day – and provide more immediate feedback; however, they do not necessarily include nightly builds.  As a result, compiler and tool updates may break the ability to compile older projects easily without warning. Nonetheless, CI techniques are considered the more modern approach. CI jobs are often run on isolated virtual machines, and typically include automated testing as well.
When someone says a developer "broke the build", they are effectively saying that a developer checked in code which might very well have compiled (and hopefully also run properly) in their account, but does not compile (and therefore, cannot be run) in anyone else's account. This is typically due to additional developer-specific changes that were either not checked in, or (in the case of environment variables, etc.) were modifications to systems not under revision control.  One of the most common cases is remembering to check in all modified files, but forgetting to add newly created files to the repository. If the other developers check out the new code without being aware of the problem, their work may grind to a halt while they wait for the problem to be fixed (or try to fix it themselves, which can be even more problematic, if multiple developers attempt to fix the issue at the same time). This naturally can result in a significant loss of productivity.
Neutral builds are important for software development processes running at high loads with short schedules (see extreme programming, startup). Not having them means that any build that needs to be created for the software quality assurance department will use code that may be in the middle of major modifications, and which is therefore best left out of a build intended for independent validation – particularly a build being evaluated for possible release.

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

- Wikipedia: https://en.wikipedia.org/wiki/Neutral_build