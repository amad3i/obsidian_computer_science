---
title: "Petri net unfoldings"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Petri_net_unfoldings"
wikipedia_categories: ["Automata (computation)", "Theoretical computer science stubs"]
related: ["[[Deterministic automaton]]", "[[Generalized star-height problem]]", "[[Ranked alphabet]]", "[[Star-free language]]", "[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Augmented transition network]]", "[[Automata theory]]"]
---

# Petri net unfoldings

Analysis of Petri nets can be performed by means of constructing either reachable state spaces (or reachable markings) or via the process of graph-based unfolding. The prefix of a Petri net unfolding, which is an acyclic Petri net graph, contains the same information about the properties of the Petri net as the reachability graph, plus it contains information about sequence, concurrency and conflict relations between Petri net transitions and Petri net places. The advantages of the use of unfolding in practice are typically associated with the fact that the unfolding prefix is much more compact than the reachability graph of the Petri net being analysed.
Petri net unfoldings were originally introduced by Ken McMillan. Later they were studied by several authors, who improved the original criterion for producing the prefix of the unfolding in terms of its compactness and hence efficient analysis. 
There are applications of Petri net unfoldings in the analysis and synthesis of concurrent systems and asynchronous circuits. The latter is normally achieved through the use of Signal transition graphs (STGs).

## Related

- [[Deterministic automaton]]
- [[Generalized star-height problem]]
- [[Ranked alphabet]]
- [[Star-free language]]
- [[Abstract machine]]
- [[Alternating timed automaton]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Augmented transition network]]
- [[Automata theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Petri_net_unfoldings