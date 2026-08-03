---
title: "Diff"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Diff"
wikipedia_categories: ["1974 software", "Data differencing", "Formal languages", "Free file comparison tools", "Inferno (operating system) commands", "Pattern matching", "Plan 9 commands", "Standard Unix programs"]
related: ["[[AWK]]", "[[Kill (command)]]", "[[Metacharacter]]", "[[Parser Grammar Engine]]", "[[Regular expression]]", "[[Terminal and nonterminal symbols]]", "[[Yacc]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]"]
---

# Diff

diff is a shell command that compares the content of files and reports differences. The term diff is also used to identify the output of the command and is used as a verb for running the command. To diff files, one runs diff to create a diff.
Typically, the command is used to compare text files, but it does support comparing binary files. If one of the input files contains non-textual data, the command defaults to brief-mode, reporting only a summary indication of whether the files differ. With the --text option, it always reports line-based differences; however, the output may be difficult to understand, as binary data is generally not structured in lines like text.
Although the command is primarily used ad hoc to analyze changes between two files, a special use is for creating a patch file for use with the patch command – which was specifically designed to use a diff output report as a patch file.
POSIX standardized the diff and patch commands including their shared file format.

## Related

- [[AWK]]
- [[Kill (command)]]
- [[Metacharacter]]
- [[Parser Grammar Engine]]
- [[Regular expression]]
- [[Terminal and nonterminal symbols]]
- [[Yacc]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Diff