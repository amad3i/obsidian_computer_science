---
title: "Accuracy paradox"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Accuracy_paradox"
wikipedia_categories: ["Statistical paradoxes", "Statistics stubs"]
related: ["[[Aggregate pattern]]", "[[Artificial precision]]", "[[Astrostatistics]]", "[[Bayesian inference using Gibbs sampling]]", "[[Blumenthal's zero–one law]]", "[[Canonical correspondence analysis]]", "[[Combinatorial data analysis]]", "[[Common-method variance]]", "[[Constraint (information theory)]]", "[[Cumulative flow diagram]]"]
---

# Accuracy paradox

The accuracy paradox is the paradoxical finding that accuracy is not a good metric for predictive models when classifying in predictive analytics.  This is because a simple model may have a high level of accuracy but too crude to be useful.  For example, if the incidence of category A is dominant, being found in 99% of cases, then predicting that every case is category A will have an accuracy of 99%.  Precision and recall are better measures in such cases.
The underlying issue is that there is a class imbalance between the positive class and the negative class. Prior probabilities for these classes need to be accounted for in error analysis. Precision and recall help, but precision too can be biased by unbalanced class priors in the test sets.

## Related

- [[Aggregate pattern]]
- [[Artificial precision]]
- [[Astrostatistics]]
- [[Bayesian inference using Gibbs sampling]]
- [[Blumenthal's zero–one law]]
- [[Canonical correspondence analysis]]
- [[Combinatorial data analysis]]
- [[Common-method variance]]
- [[Constraint (information theory)]]
- [[Cumulative flow diagram]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Accuracy_paradox