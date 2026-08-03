---
title: "Independent equation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Independent_equation"
wikipedia_categories: ["Linear algebra", "Linear algebra stubs"]
related: ["[[Asymmetric norm]]", "[[Eigengap]]", "[[Hamming space]]", "[[K-frame]]", "[[Lapped transform]]", "[[Liouville space]]", "[[Locally finite operator]]", "[[Matrix pencil]]", "[[Mixed linear complementarity problem]]", "[[Modeshape]]"]
---

# Independent equation

An independent equation is an equation in a system of simultaneous equations which cannot be derived algebraically from the other equations. The concept typically arises in the context of linear equations. If it is possible to duplicate one of the equations in a system by multiplying each of the other equations by some number (potentially a different number for each equation) and summing the resulting equations, then that equation is dependent on the others. But if this is not possible, then that equation is independent of the others.
If an equation is independent of the other equations in its system, then it provides information beyond that which is provided by the other equations. In contrast, if an equation is dependent on the others, then it provides no information not contained in the others collectively, and the equation can be dropped from the system without any information loss.

The number of independent equations in a system equals the rank of the augmented matrix of the system—the system's coefficient matrix with one additional column appended, that column being the column vector of constants.
The number of independent equations in a system of  consistent equations (a system that has at least one solution) can never be greater than the number of unknowns. Equivalently, if a system has more independent equations than unknowns, it is inconsistent and has no solutions.
The concepts of dependence and independence of systems
are partially generalized in numerical linear algebra by the condition number, which (roughly) measures how close a system
of equations is to being dependent (a condition number of 
infinity is a dependent system, and a system of orthogonal equations is maximally independent and has a condition number
close to 1.)

## Related

- [[Asymmetric norm]]
- [[Eigengap]]
- [[Hamming space]]
- [[K-frame]]
- [[Lapped transform]]
- [[Liouville space]]
- [[Locally finite operator]]
- [[Matrix pencil]]
- [[Mixed linear complementarity problem]]
- [[Modeshape]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Independent_equation