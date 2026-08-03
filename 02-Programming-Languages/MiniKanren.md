---
title: "MiniKanren"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/MiniKanren"
wikipedia_categories: ["Logic programming", "Programming languages"]
related: ["[[A+ (programming language)]]", "[[ABAP]]", "[[Abductive logic programming]]", "[[Ada (programming language)]]", "[[Address programming language]]", "[[Advice taker]]", "[[ALGOL 68]]", "[[Answer set programming]]", "[[Apache Groovy]]", "[[APL (programming language)]]"]
---

# MiniKanren

miniKanren is a family of programming languages for relational programming, first developed by Will Byrd. As relations are bidirectional, if miniKanren is given an expression and a desired output, miniKanren can run the expression "backward", finding all possible inputs to the expression that produce the desired output. This bidirectional behavior allows the user to constrain both the input to the program and the result of the program simultaneously. miniKanren performs an interleaved search which will eventually find any solution that exists, even if any one branch of the search tree is infinitely long and contains no solutions. If no solution exists, miniKanren may search forever if the search tree is infinite.
An example of miniKanren code is evalo, a relational goal that relates expressions to the values that they evaluate to. When evalo is called in miniKanren like so: (evalo q q), it will generate quines, that is, expressions q that when run will evaluate to themselves.
The book The Reasoned Schemer uses miniKanren to demonstrate relational programming, and provides a complete implementation in Scheme. The core of the language fits on two printed pages. The Scheme implementation of miniKanren is designed to be easily understood, modified, and extended.
microKanren is another language in the miniKanren family, notable for its minimalist implementation in fewer than 40 lines of Scheme.
αleanTAP is a program written in αKanren, an extension of miniKanren for nominal logic. Given a theorem, it can find a proof, making it a theorem-prover. Given a proof, it can find the theorem, making it a theorem-checker. Given part of a proof and part of a theorem, it will fill in the missing parts of the proof and the theorem, making it a theorem-explorer.
There are implementations of miniKanren in Clojure, Dart, Haskell, JavaScript, Python, Racket, Ruby, Scala, and Swift. The canonical implementation is an embedded language in Scheme. The Clojure core.logic library was inspired by miniKanren.
The name kanren comes from a Japanese word (関連) meaning "relation".

## Related

- [[A+ (programming language)]]
- [[ABAP]]
- [[Abductive logic programming]]
- [[Ada (programming language)]]
- [[Address programming language]]
- [[Advice taker]]
- [[ALGOL 68]]
- [[Answer set programming]]
- [[Apache Groovy]]
- [[APL (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MiniKanren