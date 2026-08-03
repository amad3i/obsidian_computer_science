---
title: "Forward chaining"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Forward_chaining"
wikipedia_categories: ["Expert systems", "Logic programming"]
related: ["[[Artificial intelligence in fraud detection]]", "[[Production system (computer science)]]", "[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Autoepistemic logic]]", "[[Backward chaining]]", "[[Belief revision]]", "[[BNR Prolog]]", "[[Business rule management system]]"]
---

# Forward chaining

Forward chaining  (or forward reasoning) is one of the two main methods of reasoning when using an inference engine and can be described logically as repeated application of modus ponens. Forward chaining is a popular implementation strategy for expert systems, business and production rule systems. The opposite of forward chaining is backward chaining.
Forward chaining starts with the available data and uses inference rules to extract more data (from an end user, for example) until a goal is reached. An inference engine using forward chaining searches the inference rules until it finds one where the antecedent (If clause) is known to be true. When such a rule is found, the engine can conclude, or infer, the consequent (Then clause), resulting in the addition of new information to its data.  
Inference engines will iterate through this process until a goal is reached.

## Related

- [[Artificial intelligence in fraud detection]]
- [[Production system (computer science)]]
- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Autoepistemic logic]]
- [[Backward chaining]]
- [[Belief revision]]
- [[BNR Prolog]]
- [[Business rule management system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Forward_chaining