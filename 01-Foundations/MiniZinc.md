---
title: "MiniZinc"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/MiniZinc"
wikipedia_categories: ["Algebraic modeling languages", "Computer algebra systems", "Mathematical modeling", "Mathematical optimization software", "Numerical programming languages", "Numerical software", "Scripting languages", "Supply chain analytics"]
related: ["[[AMPL]]", "[[Analytica (software)]]", "[[Maple (software)]]", "[[Mathcad]]", "[[MATLAB]]", "[[Wolfram Mathematica]]", "[[LabVIEW]]", "[[PottersWheel]]", "[[SAS (software)]]", "[[Simulink]]"]
---

# MiniZinc

MiniZinc is a constraint modelling language (or algebraic modeling language) to describe and solve high-complexity problems using a variety of well-known solving paradigms for combinatorial problems including constraint programming, integer programming, SAT, and SMT. 
Following the constraint programming paradigm, in MiniZinc a problem is specified in terms of known values (parameters), unknown values (decision variables), and the relationship (constraints) between these values. MiniZinc promotes the use of global constraints to model well-known structures in problems. These global constraints improve the clarity of the model and allow solvers to use the most effective method to exploit the structure. A MiniZinc problem instance is translated (or flattened) to a level at which it only supports constraints that are supported by the target solver and then given to the solver using its preferred format. Currently MiniZinc can communicate with solvers using its own format "FlatZinc" or .nl files. 
A big advantage of MiniZinc is the possibility to use different solvers from the same MiniZinc instance. MiniZinc supports many solvers, both open source and commercial software, including CBC, Choco, Chuffed, HiGHS, Gurobi, IPOPT, and OR-Tools.  
MiniZinc is interoperable with other  languages such as R and Python.

## Related

- [[AMPL]]
- [[Analytica (software)]]
- [[Maple (software)]]
- [[Mathcad]]
- [[MATLAB]]
- [[Wolfram Mathematica]]
- [[LabVIEW]]
- [[PottersWheel]]
- [[SAS (software)]]
- [[Simulink]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MiniZinc