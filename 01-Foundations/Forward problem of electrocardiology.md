---
title: "Forward problem of electrocardiology"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Forward_problem_of_electrocardiology"
wikipedia_categories: ["Cardiac electrophysiology", "Cardiac procedures", "Electrodiagnosis", "Electrophysiology", "Mathematical modeling", "Mathematics in medicine", "Medical tests", "Numerical analysis"]
related: ["[[Bidomain model]]", "[[Bueno-Orovio–Cherry–Fenton model]]", "[[Iterative rational Krylov algorithm]]", "[[Model order reduction]]", "[[Movable cellular automaton]]", "[[Proper generalized decomposition]]", "[[Surrogate model]]", "[[Variational multiscale method]]", "[[Vector field reconstruction]]", "[[2Sum]]"]
---

# Forward problem of electrocardiology

The forward problem of electrocardiology is a computational and mathematical approach to study the electrical activity of the heart through the body surface. The principal aim of this study is to computationally reproduce an electrocardiogram (ECG), which has important clinical relevance to define cardiac pathologies such as ischemia and infarction, or to test pharmaceutical intervention. Given their important functionalities and the relative small invasiveness, the electrocardiography techniques are used quite often as clinical diagnostic tests. Thus, it is natural to proceed to computationally reproduce an ECG, which means to mathematically model the cardiac behaviour inside the body.
The three main parts of a forward model for the ECG are:

a model for the cardiac electrical activity;
a model for the diffusion of the electrical potential inside the torso, which represents the extracardiac region;
some specific heart-torso coupling conditions.
Thus, to obtain an ECG, a mathematical electrical cardiac model must be considered, coupled with a diffusive model in a passive conductor that describes the electrical propagation inside the torso.
The coupled model is usually a three-dimensional model expressed in terms of partial differential equations. Such model is typically solved by means of finite element method for the solution's space evolution and semi-implicit numerical schemes involving finite differences for the solution's time evolution. However, the computational costs of such techniques, especially with three dimensional simulations, are quite high. Thus, simplified models are often considered, solving for example the heart electrical activity independently from the problem on the torso. To provide realistic results, three dimensional anatomically realistic models of the heart and the torso must be used.
Another possible simplification is a dynamical model made of three ordinary differential equations.

## Related

- [[Bidomain model]]
- [[Bueno-Orovio–Cherry–Fenton model]]
- [[Iterative rational Krylov algorithm]]
- [[Model order reduction]]
- [[Movable cellular automaton]]
- [[Proper generalized decomposition]]
- [[Surrogate model]]
- [[Variational multiscale method]]
- [[Vector field reconstruction]]
- [[2Sum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Forward_problem_of_electrocardiology