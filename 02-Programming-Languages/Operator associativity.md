---
title: "Operator associativity"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Operator_associativity"
wikipedia_categories: ["Operators (programming)", "Parsing", "Programming language topics"]
related: ["[[Indexer (programming)]]", "[[Abstract syntax]]", "[[Ad hoc polymorphism]]", "[[Attribute grammar]]", "[[Bitwise ternary logic instruction]]", "[[Camlp4]]", "[[Cognitive dimensions of notations]]", "[[Comparative illusion]]", "[[Compiler-compiler]]", "[[Concatenation]]"]
---

# Operator associativity

In programming language theory, the associativity of an operator is a property that determines how operators of the same precedence are grouped in the absence of parentheses.  If an operand is both preceded and followed by operators (for example, ^ 3 ^), and those operators have equal precedence, then the operand may be used as input to two different operations (i.e. the two operations indicated by the two operators). The choice of which operations to apply the operand to, is determined by the associativity of the operators. Operators may be associative (meaning the operations can be grouped arbitrarily), left-associative (meaning the operations are grouped from the left), right-associative (meaning the operations are grouped from the right) or non-associative (meaning operations cannot be chained, often because the output type is incompatible with the input types). The associativity and precedence of an operator is a part of the definition of the programming language; different programming languages may have different associativity and precedence for the same type of operator.
Consider the expression a ~ b ~ c. If the operator ~ has left associativity, this expression would be interpreted as (a ~ b) ~ c. If the operator has right associativity, the expression would be interpreted as a ~ (b ~ c). If the operator is non-associative, the expression might be a syntax error, or it might have some special meaning. Some mathematical operators have inherent associativity. For example, subtraction and division, as used in conventional math notation, are inherently left-associative. Addition and multiplication, by contrast, are both left and right associative.  (e.g. (a * b) * c = a * (b * c)).
Many programming language manuals provide a table of operator precedence and associativity; see, for example, the table for C and C++.
The concept of notational associativity described here is related to, but different from, the mathematical associativity. An operation that is mathematically associative, by definition requires no notational associativity. (For example, addition has the associative property, therefore it does not have to be either left associative or right associative.) An operation that is not mathematically associative, however, must be notationally left-, right-, or non-associative. (For example, subtraction does not have the associative property, therefore it must have notational associativity.)

## Related

- [[Indexer (programming)]]
- [[Abstract syntax]]
- [[Ad hoc polymorphism]]
- [[Attribute grammar]]
- [[Bitwise ternary logic instruction]]
- [[Camlp4]]
- [[Cognitive dimensions of notations]]
- [[Comparative illusion]]
- [[Compiler-compiler]]
- [[Concatenation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Operator_associativity