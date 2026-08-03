---
title: "Nonblocking minimal spanning switch"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Nonblocking_minimal_spanning_switch"
wikipedia_categories: ["Graph algorithms", "Telephone exchanges"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[Blossom algorithm]]"]
---

# Nonblocking minimal spanning switch

A nonblocking minimal spanning switch is a concept developed in the 1950s to reduce the costs of telephone exchanges in the Bell System by reducing the number of the most expensive components of a telephone switch.
This reflects a key problem in the AT&T Bell System prior to divestiture in 1984, which was 

providing satisfactory (from the customer point of view) end-to-end service at the lowest possible cost.

The Operations Research Department at Bell Labs and other technical staff focused on developing mathematics and computer tools to minimize costs subject to constraints.  In the context of making telephone connections, this was taken to mean minimizing the number of expensive switch components subject to the constraint of still being able to connect any two idle telephones on request. 
Historically, in telephone switches, connections between callers were arranged with Strowger switches, which were large, expensive banks of electromechanical relays.  Later the Strowger switches were replaced by crossbar switches, which used a matrix of connections (called crosspoints) to set up calls. 
In the 1940s and 1950s, engineers in Bell Lab began an extended series of mathematical investigations into methods for reducing the size and expense of the "switched fabric" needed to implement a telephone exchange. For this purpose a crossbar switch was described as  a device that can connect N inputs to N outputs in any combination and uses as few crosspoints as possible.   The term "non-blocking" means that if the switch is not defective, it can always make the connection.  The term "minimal" means that it has the fewest possible crosspoints, and therefore the minimal expense.
One successful mathematical analysis was performed by Charles Clos (French pronunciation: [ʃaʁl klo]), and a switched fabric constructed of smaller switches is called a Clos network.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]
- [[Blossom algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nonblocking_minimal_spanning_switch