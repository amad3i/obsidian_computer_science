---
title: "No free lunch in search and optimization"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/No_free_lunch_in_search_and_optimization"
wikipedia_categories: ["Mathematical optimization", "Theorems in computational complexity theory"]
related: ["[[Algorithmic problems on convex sets]]", "[[Analysis of Boolean functions]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Basis pursuit]]", "[[Basis pursuit denoising]]", "[[Bauer maximum principle]]", "[[Bayesian efficiency]]", "[[Bilinear program]]", "[[Binary constraint]]"]
---

# No free lunch in search and optimization

In computational complexity and optimization the no free lunch theorem is a result that states that for certain types of mathematical problems, the computational cost of finding a solution, averaged over all problems in the class, is the same for any solution method. The name alludes to the saying "no such thing as a free lunch", that is, no method offers a "short cut".  This is under the assumption that the search space is a probability density function. It does not apply to the case where the search space has underlying structure (e.g., is a differentiable function) that can be exploited more efficiently (e.g., Newton's method in optimization) than random search or even has closed-form solutions (e.g., the extrema of a quadratic polynomial) that can be determined without search at all. For such probabilistic assumptions, the outputs of all procedures solving a particular type of problem are statistically identical. A colourful way of describing such a circumstance, introduced by David Wolpert and William G. Macready in connection with the problems of search and optimization,
is to say that  there is no free lunch. Wolpert had previously derived no free lunch theorems for machine learning (statistical inference). 
Before Wolpert's article was published, Cullen Schaffer independently proved a restricted version of one of Wolpert's theorems and used it to critique the current state of machine learning research on the problem of induction.
In the "no free lunch" metaphor, each "restaurant" (problem-solving procedure) has a "menu" associating each "lunch plate" (problem) with a "price" (the performance of the procedure in solving the problem). The menus of restaurants are identical except in one regard – the prices are shuffled from one restaurant to the next. For an omnivore who is as likely to order each plate as any other, the average cost of lunch does not depend on the choice of restaurant. But a vegan who goes to lunch regularly with a carnivore who seeks economy might pay a high average cost for lunch. To methodically reduce the average cost, one must use advance knowledge of a) what one will order and b) what the order will cost at various restaurants. That is, improvement of performance in problem-solving hinges on using prior information to match procedures to problems.
In formal terms, there is no free lunch when the probability distribution on problem instances is such that all problem solvers have identically distributed results. In the case of search, a problem instance in this context is a particular objective function, and a result is a sequence of values obtained in evaluation of candidate solutions in the domain of the function. For typical interpretations of results, search is an optimization process. There is no free lunch in search if and only if the distribution on objective functions is invariant under permutation of the space of candidate solutions. This condition does not hold precisely in practice, but an "(almost) no free lunch" theorem suggests that it holds approximately.

## Related

- [[Algorithmic problems on convex sets]]
- [[Analysis of Boolean functions]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Basis pursuit]]
- [[Basis pursuit denoising]]
- [[Bauer maximum principle]]
- [[Bayesian efficiency]]
- [[Bilinear program]]
- [[Binary constraint]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/No_free_lunch_in_search_and_optimization