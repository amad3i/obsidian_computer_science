---
title: "Option–operand separation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Option–operand_separation"
wikipedia_categories: ["Object-oriented programming", "Programming language theory stubs"]
related: ["[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[Call super]]", "[[Circle–ellipse problem]]", "[[Class variable]]", "[[Climate Data Exchange]]"]
---

# Option–operand separation

Option–operand separation is a principle of imperative computer programming. It was devised by Bertrand Meyer as part of his pioneering work on the Eiffel programming language.
It states that an operation's arguments should contain only operands — understood as information necessary to its operation — and not options — understood as auxiliary information. Options are supposed to
be set in separate operations.
The motivations for this are:

Ease of learning: Beginners do not have to concern themselves with setting options.
Wide spectrum coverage:  Experts can still set options using the auxiliary operations.
Evolution. Options are more likely to change than operands, so the parameter list to the operation remains more stable.

## Related

- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[Call super]]
- [[Circle–ellipse problem]]
- [[Class variable]]
- [[Climate Data Exchange]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Option–operand_separation