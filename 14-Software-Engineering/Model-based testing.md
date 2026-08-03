---
title: "Model-based testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Model-based_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Model-based testing

In computing, model-based testing is an approach to testing that leverages model-based design for designing and possibly executing tests. As shown in the diagram on the right, a model can represent the desired behavior of a system under test (SUT). Or a model can represent testing strategies and environments.
A model describing a SUT is usually an abstract, partial presentation of the SUT's desired behavior.
Test cases derived from such a model are functional tests on the same level of abstraction as the model.
These test cases are collectively known as an abstract test suite.
An abstract test suite cannot be directly executed against an SUT because the suite is on the wrong level of abstraction.
An executable test suite needs to be derived from a corresponding abstract test suite.
The executable test suite can communicate directly with the system under test.
This is achieved by mapping the abstract test cases to 
concrete test cases suitable for execution. In some model-based testing environments, models contain enough information to generate executable test suites directly.
In others, elements in the abstract test suite must be mapped to specific statements or method calls in the software to create a concrete test suite. This is called solving the "mapping problem".
In the case of online testing (see below), abstract test suites exist only conceptually but not as explicit artifacts.
Tests can be derived from models in different ways. Because testing is usually experimental and based on heuristics,
there is no known single best approach for test derivation.
It is common to consolidate all test derivation related parameters into a
package that is often known as "test requirements", "test purpose" or even "use case(s)".
This package can contain information about those parts of a model that should be focused on, or the conditions for finishing testing (test stopping criteria).
Because test suites are derived from models and not from source code, model-based testing is usually seen as one form of black-box testing.

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

- Wikipedia: https://en.wikipedia.org/wiki/Model-based_testing