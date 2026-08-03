---
title: "Essential complexity"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Essential_complexity"
wikipedia_categories: ["Software metrics", "Software project management"]
related: ["[[Software parametric models]]", "[[ABC Software Metric]]", "[[Agile contracts]]", "[[Agile software development]]", "[[Bauhaus Project (computing)]]", "[[Cockburn Scale]]", "[[Code coverage]]", "[[Cohesion (computer science)]]", "[[COSMIC functional size measurement]]", "[[Coupling (computer programming)]]"]
---

# Essential complexity

Essential complexity is a numerical measure defined by Thomas J. McCabe, Sr., in his highly cited, 1976 paper better known for introducing cyclomatic complexity. McCabe defined essential complexity as the cyclomatic complexity of the reduced CFG (control-flow graph) after iteratively replacing (reducing) all structured programming control structures, i.e. those having a single entry point and a single exit point (for example if-then-else and while loops) with placeholder single statements.
McCabe's reduction process is intended to simulate the conceptual replacement of control structures (and actual statements they contain) with subroutine calls, hence the requirement for the control structures to have a single entry and a single exit point. (Nowadays a process like this would fall under the umbrella term of refactoring.) All structured programs evidently have an essential complexity of 1 as defined by McCabe because they can all be iteratively reduced to a single call to a top-level subroutine. As McCabe explains in his paper, his essential complexity metric was designed to provide a measure of how far off this ideal (of being completely structured) a given program was. Thus greater than 1 essential complexity numbers, which can only be obtained for non-structured programs, indicate that they are further away from the structured programming ideal.
To avoid confusion between various notions of reducibility to structured programs, it's important to note that McCabe's paper briefly discusses and then operates in the context of a 1973 paper by S. Rao Kosaraju, which gave a refinement (or alternative view) of the structured program theorem. The seminal 1966 paper of Böhm and Jacopini showed that all programs can be [re]written using only structured programming constructs, (aka the D structures: sequence, if-then-else, and while-loop), however, in transforming a random program into a structured program additional variables may need to be introduced (and used in the tests) and some code may be duplicated.
In their paper, Böhm and Jacopini conjectured, but did not prove that it was necessary to introduce such additional variables for certain kinds of non-structured programs in order to transform them into structured programs. An example of program (that we now know) does require such additional variables is a loop with two conditional exits inside it. In order to address the conjecture of Böhm and Jacopini, Kosaraju defined a more restrictive notion of program reduction than the Turing equivalence used by Böhm and Jacopini. Essentially, Kosaraju's notion of reduction imposes, besides the obvious requirement that the two programs must compute the same value (or not finish) given the same inputs, that the two programs must use the same primitive actions and predicates, the latter understood as expressions used in the conditionals. Because of these restrictions, Kosaraju's reduction does not allow the introduction of additional variables; assigning to these variables would create new primitive actions and testing their values would change the predicates used in the conditionals. Using this more restrictive notion of reduction, Kosaraju proved Böhm and Jacopini's conjecture, namely that a loop with two exits cannot be transformed into a structured program without introducing additional variables, but went further and proved that programs containing multi-level breaks (from loops) form a hierarchy, such that one can always find a program with multi-level breaks of depth n that cannot be reduced to a program of multi-level breaks with depth less than n, again without introducing additional variables.
McCabe notes in his paper that in view of Kosaraju's results, he intended to find a way to capture the essential properties of non-structured programs in terms of their control-flow graphs. He proceeds by first identifying the control-flow graphs corresponding to the smallest non-structured programs (these include branching into a loop, branching out of a loop, and their if-then-else counterparts) which he uses to formulate a theorem analogous to Kuratowski's theorem, and thereafter he introduces his notion of essential complexity in order to give a scale answer ("measure of the structuredness of a program" in his words) rather than a yes/no answer to the question of whether a program's control-flow graph is structured or not. Finally, the notion of reduction used by McCabe to shrink the CFG is not the same as Kosaraju's notion of reducing flowcharts. The reduction defined on the CFG does not know or care about the program's inputs, it is simply a graph transformation.
For example, the following C program fragment has an essential complexity of 1, because the inner if statement and the for can be reduced, i.e. it is a structured program.

The following C program fragment has an essential complexity of four; its CFG is irreducible. The program finds the first row of z which is all zero and puts that index in i; if there is none, it puts -1 in i.

The idea of CFG reducibility by successive collapses of sub-graphs (ultimately to a single node for well-behaved CFGs) is also used in modern compiler optimization. However the notion from structured programming of single-entry and single-exit control structure is replaced with that of natural loop, which is defined as a "single-entry, multiple-exit loop, with only a single branch back to the entry from within it". The areas of the CFG that cannot be reduced to natural loops are called improper regions; these regions end up having a fairly simple definition: multiple-entry, strongly connected components of the CFG. The simplest improper region is thus a loop with two entry points. Multiple exits do not cause analysis problems in modern compilers. Improper regions (multiple-entries into loops) do cause additional difficulties in optimizing code.

## Related

- [[Software parametric models]]
- [[ABC Software Metric]]
- [[Agile contracts]]
- [[Agile software development]]
- [[Bauhaus Project (computing)]]
- [[Cockburn Scale]]
- [[Code coverage]]
- [[Cohesion (computer science)]]
- [[COSMIC functional size measurement]]
- [[Coupling (computer programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Essential_complexity