---
title: "Trigram search"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Trigram_search"
wikipedia_categories: ["Search algorithms", "String matching algorithms"]
related: ["[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]", "[[Amplitude amplification]]", "[[Anytime A-]]", "[[Anytime algorithm]]", "[[B-]]", "[[Backjumping]]", "[[Backtracking]]"]
---

# Trigram search

Trigram search is a method of searching for text when the exact syntax or spelling of the target object is not precisely known or when queries may be regular expressions. It finds objects which have the most matches against three-character substrings (i.e. trigrams) of the search terms, which are generally near matches. Two strings with many shared trigrams can be expected to be very similar. Trigrams also allow for efficiently creating search engine indexes for searches that are regular expressions or match the text inexactly. Indexes can significantly accelerate searches. A threshold for number of trigram matches can be specified as a cutoff point, after a result is unmatched.
Using trigrams for accelerating searches is a technique used in some systems for code searching, in situations in which queries that are regular expressions may be useful, in search engines such as Elasticsearch, as well as in databases such as PostgreSQL.

## Related

- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]
- [[Amplitude amplification]]
- [[Anytime A-]]
- [[Anytime algorithm]]
- [[B-]]
- [[Backjumping]]
- [[Backtracking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Trigram_search