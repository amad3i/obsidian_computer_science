---
title: "Augmented transition network"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Augmented_transition_network"
wikipedia_categories: ["Automata (computation)", "Natural language parsing"]
related: ["[[Abstract machine]]", "[[Alternating timed automaton]]", "[[Alternating tree automata]]", "[[Asynchronous circuit]]", "[[Attempto Controlled English]]", "[[Automata theory]]", "[[Automatic sequence]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[Boolean differential calculus]]", "[[ChatScript]]"]
---

# Augmented transition network

An augmented transition network (ATN) is a type of graph theoretic structure used in the operational definition of formal languages, used especially in parsing relatively complex natural languages, and having wide application in artificial intelligence. An ATN can, theoretically, analyze the structure of any sentence, however complicated. ATN are modified transition networks and an extension of RTNs.
ATNs build on the idea of using finite-state machines (Markov model) to parse sentences. W. A. Woods in "Transition Network Grammars for Natural Language Analysis" argues that by adding a recursive mechanism to a finite state model, parsing can be achieved much more efficiently. Instead of building an automaton for a particular sentence, a collection of transition graphs are built. A grammatically correct sentence is parsed by reaching a final state in any state graph. Transitions between these graphs are simply subroutine calls from one state to any initial state on any graph in the network. A sentence is determined to be grammatically correct if a final state is reached by the last word in the sentence.
This model meets many of the goals set forth by the nature of language in that it captures the regularities of the language. That is, if there is a process that operates in a number of environments, the grammar should encapsulate the process in a single structure. Such encapsulation not only simplifies the grammar, but has the bonus of efficiency of operation. Another advantage of such a model is the ability to postpone decisions. Many grammars use guessing when an ambiguity comes up. This means that not enough is yet known about the sentence. By the use of recursion, ATNs solve this inefficiency by postponing decisions until more is known about a sentence.

## Related

- [[Abstract machine]]
- [[Alternating timed automaton]]
- [[Alternating tree automata]]
- [[Asynchronous circuit]]
- [[Attempto Controlled English]]
- [[Automata theory]]
- [[Automatic sequence]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[Boolean differential calculus]]
- [[ChatScript]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Augmented_transition_network