---
title: "Metamorphic testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Metamorphic_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Metamorphic testing

Metamorphic testing (MT) is a property-based software testing technique, which can be an effective approach for addressing the test oracle problem and test case generation problem.  The test oracle problem is the difficulty of determining the expected outcomes of selected test cases or to determine whether the actual outputs agree with the expected outcomes.
Metamorphic relations (MRs) are necessary properties of the intended functionality of the software, and must involve multiple executions of the software.  Consider, for example, a program that implements sin x correct to 100 significant figures; a metamorphic relation for sine functions is "sin (π − x) = sin x".  Thus, even though the expected value of sin x1 for the source test case x1 = 1.234 correct to the required accuracy is not known, a follow-up test case x2 = π − 1.234 can be constructed.
We can verify whether the actual outputs produced by the program under test from the source test case and the follow-up test case are consistent with the MR in question.  Any inconsistency (after taking rounding errors into consideration) indicates a failure of the program, caused by a fault in the implementation.
MRs are not limited to programs with numerical inputs or equality relations. As an example, when testing a booking website, a web search for accommodation in Sydney, Australia, returns 1,671 results; are the results of this search correct and complete? This is a test oracle problem. Based on a metamorphic relation, we may filter the price range or star rating and apply the search again; it should return a subset of the previous results. A violation of this expectation would similarly reveal a failure of the system.
Metamorphic testing was invented by T.Y. Chen in a technical report in 1998.
Since then, more than 750 papers have been published by international researchers and practitioners, working further on the theory and practice of MT in real-life applications. Some examples include web services,
computer graphics,
embedded systems,
simulation and modeling,
machine learning,
decision support,
bioinformatics,
components,
numerical analysis, compilers, and even quantum computing
The first major survey of MT was conducted in 2016.
It was followed by another major survey in 2018, which highlights the challenges and opportunities and clarifies common misunderstandings.
Although MT was initially proposed as a software verification technique, it was later developed into a paradigm that covers verification, validation, and other types of software quality assessment. MT can be applied independently, and can also be combined with other static and dynamic software analysis techniques such as proving and debugging.
In August 2018, Google acquired GraphicsFuzz, a startup from Imperial College London, to apply
metamorphic testing to graphics device drivers for Android smartphones.

## Related

- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]
- [[All-pairs testing]]
- [[Analytical Performance Modeling]]
- [[API testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Metamorphic_testing