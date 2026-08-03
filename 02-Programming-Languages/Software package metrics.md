---
title: "Software package metrics"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Software_package_metrics"
wikipedia_categories: ["Object-oriented programming", "Software metrics"]
related: ["[[Coupling (computer programming)]]", "[[ABC Software Metric]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Bauhaus Project (computing)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Call super]]"]
---

# Software package metrics

Various software package metrics are used in modular programming. They have been mentioned by Robert Cecil Martin in his 2002 book Agile software development: principles, patterns, and practices.
The term software package here refers to a group of related classes in object-oriented programming.

Number of classes and interfaces: The number of concrete and abstract classes (and interfaces) in the package is an indicator of the extensibility of the package.
Afferent couplings (Ca): The number of classes in other packages that depend upon classes within the package is an indicator of the package's responsibility. Afferent couplings signal inward.
Efferent couplings (Ce): The number of classes in other packages that the classes in a package depend upon is an indicator of the package's dependence on externalities. Efferent couplings signal outward.
Abstractness (A): The ratio of the number of abstract classes (and interfaces) in the analyzed package to the total number of classes in the analyzed package.  The range for this metric is 0 to 1, with A=0 indicating a completely concrete package and A=1 indicating a completely abstract package.
Instability (I): The ratio of efferent coupling (Ce) to total coupling (Ce + Ca) such that I = Ce / (Ce + Ca). This metric is an indicator of the package's resilience to change.  The range for this metric is 0 to 1, with I=0 indicating a completely stable package and I=1 indicating a completely unstable package.
Distance from the main sequence (D): The perpendicular distance of a package from the idealized line A + I = 1. D is calculated as D = | A + I - 1 |. This metric is an indicator of the package's balance between abstractness and stability.  A package squarely on the main sequence is optimally balanced with respect to its abstractness and stability. Ideal packages are either completely abstract and stable (I=0, A=1) or completely concrete and unstable (I=1, A=0).  The range for this metric is 0 to 1, with D=0 indicating a package that is coincident with the main sequence and D=1 indicating a package that is as far from the main sequence as possible.
Package dependency cycles: Package dependency cycles are reported along with the hierarchical paths of packages participating in package dependency cycles.

## Related

- [[Coupling (computer programming)]]
- [[ABC Software Metric]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Bauhaus Project (computing)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Call super]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Software_package_metrics