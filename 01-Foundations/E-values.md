---
title: "E-values"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/E-values"
wikipedia_categories: ["Probability theory", "Statistical concepts", "Statistical hypothesis testing"]
related: ["[[Additive process]]", "[[Additive smoothing]]", "[[Almost surely]]", "[[Asymptotic geometry]]", "[[Big O in probability notation]]", "[[Blackwell-Girshick equation]]", "[[Blumenthal's zero–one law]]", "[[Brownian motion and Riemann zeta function]]", "[[Carleman's condition]]", "[[Carré du champ operator]]"]
---

# E-values

In statistical hypothesis testing, e-values quantify the evidence in the data against a null hypothesis (e.g., "the coin is fair", or, in a medical context, "this new treatment has no effect"). They serve as a more robust alternative to p-values, addressing some shortcomings of the latter.
In contrast to p-values, e-values can deal with optional continuation: e-values of subsequent experiments (e.g. clinical trials concerning the same treatment) may simply be multiplied to provide a new, "product" e-value that represents the evidence in the joint experiment. This works even if, as often happens in practice, the decision to perform later experiments may depend in vague, unknown ways on the data observed in earlier experiments, and it is not known beforehand how many trials will be conducted: the product e-value remains a meaningful quantity, leading to tests with Type-I error control. For this reason, e-values and their sequential extension, the e-process, are the fundamental building blocks for anytime-valid statistical methods (e.g. confidence sequences). Another advantage over p-values is that any weighted average of e-values remains an e-value, even if the individual e-values are arbitrarily dependent. This is one of the reasons why e-values have also turned out to be useful tools in multiple testing.
E-values can be interpreted in a number of different ways: first, an e-value can be interpreted as rescaling of a test that is presented on a more appropriate scale that facilitates merging them.
Second, the reciprocal of an e-value is a p-value, but not just any p-value: a special p-value for which a rejection `at level p' retains a generalized Type-I error guarantee. Third, they are broad generalizations of likelihood ratios and are also related to, yet distinct from, Bayes factors. Fourth, they have an interpretation as bets. Fifth, in a sequential context, they can also be interpreted as increments of nonnegative supermartingales. Interest in e-values has exploded since 2019, when the term 'e-value' was coined and a number of breakthrough results were achieved by several research groups. The first overview article appeared in 2023.

## Related

- [[Additive process]]
- [[Additive smoothing]]
- [[Almost surely]]
- [[Asymptotic geometry]]
- [[Big O in probability notation]]
- [[Blackwell-Girshick equation]]
- [[Blumenthal's zero–one law]]
- [[Brownian motion and Riemann zeta function]]
- [[Carleman's condition]]
- [[Carré du champ operator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/E-values