---
title: "Text parser"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Text_parser"
wikipedia_categories: ["Interactive fiction", "Parsing"]
related: ["[[Abstract syntax]]", "[[Attribute grammar]]", "[[Camlp4]]", "[[Comparative illusion]]", "[[Compiler-compiler]]", "[[Dangling else]]", "[[Definite clause grammar]]", "[[Deterministic parsing]]", "[[Extended affix grammar]]", "[[Inverse parser]]"]
---

# Text parser

In adventure games, a text parser takes typed input (a command) from the player and simplifies it to something the game can understand. Usually, words with the same meaning are turned into the same word (e.g. "take" and "get") and certain filler words are dropped (e.g. articles, or the "at" in "look at rock").
The parser makes it easier for the game's author to react on input. The author does not have to write special code to process the commands "get ye flask", "take ye flask", "get flask", "take flask", "take ye precious flask", etc. separately, as the parser will have stripped the input down to something like "take flask".
For the player, the game is more flexible, as the game has a larger vocabulary, and there are fewer guess-the-verb and guess-the-noun problems.
Parsers are used in early interactive fiction games like the Zork series, and more recently in games created by systems like Inform and TADS.

## Related

- [[Abstract syntax]]
- [[Attribute grammar]]
- [[Camlp4]]
- [[Comparative illusion]]
- [[Compiler-compiler]]
- [[Dangling else]]
- [[Definite clause grammar]]
- [[Deterministic parsing]]
- [[Extended affix grammar]]
- [[Inverse parser]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Text_parser