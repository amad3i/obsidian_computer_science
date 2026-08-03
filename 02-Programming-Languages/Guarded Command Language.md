---
title: "Guarded Command Language"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Guarded_Command_Language"
wikipedia_categories: ["Edsger W. Dijkstra", "Logic programming"]
related: ["[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Artificial intelligence in fraud detection]]", "[[Autoepistemic logic]]", "[[Belief revision]]", "[[BNR Prolog]]", "[[Circumscription (logic)]]", "[[Clause (logic)]]", "[[Closed-world assumption]]"]
---

# Guarded Command Language

The Guarded Command Language (GCL) is a programming language defined by Edsger Dijkstra for predicate transformer semantics in EWD472. It combines programming concepts in a compact way. It makes it easier to develop a program and its proof hand-in-hand, with the proof ideas leading the way; moreover, parts of a program can actually be calculated.
An important property of GCL is nondeterminism. For example, in the if-statement, several alternatives may be true, and the choice is made at runtime, when the if-statement is executed. This frees the programmer from having to make unnecessary choices and is an aid in the formal development of programs.
GCL includes the multiple assignment statement. For example, execution of the statement x, y:= y, x is done by first evaluating the righthand side values and then storing them in the lefthand variables. Thus, this statement swaps the values of x and y.
The following books discuss the development of programs using GCL:

Dijkstra, Edsger W. (1976). A Discipline of Programming. Prentice Hall. ISBN 978-0132158718.
Gries, D. (1981). The Science of Programming. Monographs in Computer Science (in English, Spanish, Japanese, Chinese, Italian, and Russian). New York: Springer Verlag. doi:10.1007/978-1-4612-5983-1. ISBN 978-0-387-96480-5. S2CID 37034126.
Dijkstra, Edsger W.; Feijen, Wim H.J. (1988). A Method of Programming. Boston, MA: Addison-Wesley Longman Publishing Co., Inc. p. 200. ISBN 978-0-201-17536-3.
Kaldewaij, Anne (1990). Programming: the derivation of algorithms. Prentice-Hall, Inc. ISBN 0132041081.
Cohen, Edward (1990). David Gries (ed.). Programming in the 1990s: An introduction to the calculation of programs. Texts and Monographs in Computer Science. Springer Verlag. doi:10.1007/978-1-4613-9706-9. ISBN 978-1-4613-9706-9. S2CID 1509875.

## Related

- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Artificial intelligence in fraud detection]]
- [[Autoepistemic logic]]
- [[Belief revision]]
- [[BNR Prolog]]
- [[Circumscription (logic)]]
- [[Clause (logic)]]
- [[Closed-world assumption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Guarded_Command_Language