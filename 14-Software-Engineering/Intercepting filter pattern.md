---
title: "Intercepting filter pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Intercepting_filter_pattern"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Intercepting filter pattern

Intercepting Filter is a JavaEE pattern which creates pluggable filters to process common services in a standard manner without requiring changes to core request processing code.  The filters intercept incoming requests and outgoing responses, allowing preprocessing and post-processing, and these filters can be added or removed unobtrusively without changing existing code.  This pattern applies reusable processing transparently before and after the actual request execution by the front and page controllers.

## Related

- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]
- [[Balking pattern]]
- [[Behavioral pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Intercepting_filter_pattern