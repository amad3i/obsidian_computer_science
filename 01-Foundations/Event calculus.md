---
title: "Event calculus"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Event_calculus"
wikipedia_categories: ["1986 introductions", "Knowledge representation", "Logic in computer science", "Logic programming", "Logical calculi"]
related: ["[[Agentive logic]]", "[[Closed-world assumption]]", "[[Frame problem]]", "[[Model elimination]]", "[[Preferential entailment]]", "[[Qualification problem]]", "[[Ramification problem]]", "[[Region connection calculus]]", "[[Situation calculus]]", "[[Spatial–temporal reasoning]]"]
---

# Event calculus

The event calculus is a logical theory for representing and reasoning about events and about the way in which they change the state of some real or artificial world. It deals both with action events, which are performed by agents, and with external events, which are outside the control of any agent.
The event calculus represents the state of the world at any time by the set of all the facts (called fluents) that hold at the time. Events initiate and terminate fluents:

The event calculus differs from most other approaches for reasoning about change by reifying time, associating events with the time at which they happen, and associating fluents with the times at which they hold.
The original version of the event calculus, introduced by Robert Kowalski and Marek Sergot in 1986, was formulated as a logic program and developed for representing narratives and database updates. Kave Eshghi showed how to use the event calculus for planning, by using abduction to generate hypothetical actions to achieve a desired state of affairs.
It was extended by Murray Shanahan and Rob Miller in the 1990s and reformulated in first-order logic with circumscription.
These and later extensions have been used to formalize non-deterministic actions, concurrent actions, actions with delayed effects, gradual changes, actions with duration, continuous change, and non-inertial fluents.
Van Lambalgen and Hamm showed how a formulation of the event calculus as a constraint logic program can be used to give an algorithmic semantics to tense and aspect in natural language.

## Related

- [[Agentive logic]]
- [[Closed-world assumption]]
- [[Frame problem]]
- [[Model elimination]]
- [[Preferential entailment]]
- [[Qualification problem]]
- [[Ramification problem]]
- [[Region connection calculus]]
- [[Situation calculus]]
- [[Spatial–temporal reasoning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Event_calculus