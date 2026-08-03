---
title: "Simulation-based optimization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Simulation-based_optimization"
wikipedia_categories: ["Mathematical optimization", "Simulation"]
related: ["[[Activation strain model]]", "[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Artificial life]]", "[[Ashfield House]]", "[[AXIS Flight Training Systems]]", "[[Backtracking line search]]", "[[Barnes–Hut simulation]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]"]
---

# Simulation-based optimization

Simulation-based optimization (also known as simply simulation optimization) integrates optimization techniques into simulation modeling and analysis. Because of the complexity of the simulation, the objective function may become difficult and expensive to evaluate. Usually, the underlying simulation model is stochastic, so that the objective function must be estimated using statistical estimation techniques (called output analysis in simulation methodology).
Once a system is mathematically modeled, computer-based simulations provide information about its behavior. Parametric simulation methods can be used to improve the performance of a system. In this method, the input of each variable is varied with other parameters remaining constant and the effect on the design objective is observed. This is a time-consuming method and improves the performance partially. To obtain the optimal solution with minimum computation and time, the problem is solved iteratively where in each iteration the solution moves closer to the optimum solution. Such methods are known as ‘numerical optimization’, ‘simulation-based optimization’ or 'simulation-based multi-objective optimization' used when more than one objective is involved.
In simulation experiment, the goal is to evaluate the effect of different values of input variables on a system. However, the interest is sometimes in finding the optimal value for input variables in terms of the system outcomes. One way could be running simulation experiments for all possible input variables. However, this approach is not always practical due to several possible situations and it just makes it intractable to run experiments for each scenario. For example, there might be too many possible values for input variables, or the simulation model might be too complicated and expensive to run for a large set of input variable values. In these cases, the goal is to iterative find optimal values for the input variables rather than trying all possible values. This process is called simulation optimization.
Specific simulation–based optimization methods can be chosen according to Figure 1 based on the decision variable types.

Optimization exists in two main branches of operations research:
Optimization parametric (static) – The objective is to find the values of the parameters, which are “static” for all states, with the goal of maximizing or minimizing a function. In this case, one can use mathematical programming, such as linear programming. In this scenario, simulation helps when the parameters contain noise or the evaluation of the problem would demand excessive computer time, due to its complexity.
Optimization control (dynamic) – This is used largely in computer science and electrical engineering. The optimal control is per state and the results change in each of them. One can use mathematical programming, as well as dynamic programming. In this scenario, simulation can generate random samples and solve complex and large-scale problems.

## Related

- [[Activation strain model]]
- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Artificial life]]
- [[Ashfield House]]
- [[AXIS Flight Training Systems]]
- [[Backtracking line search]]
- [[Barnes–Hut simulation]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simulation-based_optimization