---
title: "Runtime verification"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Runtime_verification"
wikipedia_categories: ["Formal methods", "Logic in computer science"]
related: ["[[1-in-3-SAT]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Assertion (software development)]]", "[[Bisimulation]]", "[[Boolean satisfiability problem]]", "[[CompCert]]", "[[Formal verification]]", "[[Interference freedom]]", "[[Logic in computer science]]"]
---

# Runtime verification

Runtime verification is a computing system analysis and execution approach based on extracting information from a running system and using it to detect and possibly react to observed behaviors satisfying or violating certain properties.  Some very particular properties, such as datarace and deadlock freedom, are typically desired to be satisfied by all systems and may be best implemented algorithmically.  Other properties can be more conveniently captured as formal specifications.  Runtime verification specifications are typically expressed in trace predicate formalisms, such as finite-state machines, regular expressions, context-free patterns, linear temporal logics, etc., or extensions of these.  This allows for a less ad-hoc approach than normal testing.  However, any mechanism for monitoring an executing system is considered runtime verification, including verifying against test oracles and reference implementations .  When formal requirements specifications are provided, monitors are synthesized from them and infused within the system by means of instrumentation.  Runtime verification can be used for many purposes, such as security or safety policy monitoring, debugging, testing, verification, validation, profiling, fault protection, behavior modification (e.g., recovery), etc.  Runtime verification avoids the complexity of traditional formal verification techniques, such as model checking and theorem proving, by analyzing only one or a few execution traces and by working directly with the actual system, thus scaling up relatively well and giving more confidence in the results of the analysis (because it avoids the tedious and error-prone step of  formally modelling the system), at the expense of less coverage.  Moreover, through its reflective capabilities runtime verification can be made an integral part of the target system, monitoring and guiding its execution during deployment.

## Related

- [[1-in-3-SAT]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Assertion (software development)]]
- [[Bisimulation]]
- [[Boolean satisfiability problem]]
- [[CompCert]]
- [[Formal verification]]
- [[Interference freedom]]
- [[Logic in computer science]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Runtime_verification