---
title: "Feature toggle"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Feature_toggle"
wikipedia_categories: ["Computer programming", "Software development process"]
related: ["[[Coding best practices]]", "[[Adaptive software development]]", "[[Agile contracts]]", "[[Algorave]]", "[[Alsys]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Big design up front]]", "[[Bisection (software engineering)]]"]
---

# Feature toggle

A feature toggle in software development provides an alternative to maintaining multiple feature branches in source code. A condition within the code enables or disables a feature during runtime. In agile settings the toggle is used in production, to switch on the feature on demand, for some or all the users. Thus, feature toggles do make it easier to release often. Advanced roll out strategies such as canary roll out and A/B testing are easier to handle.
Continuous delivery is supported by feature toggles, even if new releases are not deployed to production continuously. The feature is integrated into the main branch even before it is completed. The version is deployed into a test environment once, the toggle allows to turn the feature on, and test it. Software integration cycles get shorter, and a version ready to go to production can be provided.
The third use of the technique is to allow developers to release a version of a product that has unfinished features. These unfinished features are hidden (toggled) so that they do not appear in the user interface. There is less effort to merge features into and out of the productive branch, and hence allows many small incremental versions of software.
A feature toggle is also called feature switch, feature flag, feature gate, feature flipper, or conditional feature.

## Related

- [[Coding best practices]]
- [[Adaptive software development]]
- [[Agile contracts]]
- [[Algorave]]
- [[Alsys]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Big design up front]]
- [[Bisection (software engineering)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Feature_toggle