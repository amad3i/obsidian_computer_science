---
title: "Input Field Separators"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Input_Field_Separators"
wikipedia_categories: ["Computer science stubs", "Unix"]
related: ["[[ACM SIGOPS Annual Technical Conference]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[Asynchrony (computer programming)]]", "[[Attentive user interface]]", "[[Automatic mutual exclusion]]", "[[Behavior authoring]]", "[[Behavioral modeling in computer-aided design]]"]
---

# Input Field Separators

For many command line interpreters (“shell”) of Unix operating systems, the input field separators or internal field separators or $IFS shell variable holds characters used to separate text into tokens.
The value of IFS, (in the bash shell) typically includes the space, tab, and the newline characters by default. These whitespace characters can be visualized by issuing the "declare" command in the bash shell or printing IFS with commands like printf %s "$IFS" | od -c, printf "%q\n" "$IFS" or printf %s "$IFS" | cat -A (the latter two commands being only available in some shells and on some systems).
From the Bash, version 4 man page:

The shell treats each character of $IFS as a delimiter, and splits the results of the other expansions into words on these characters.
If IFS is unset, or its value is exactly <space><tab><newline>, the default, then sequences of <space>, <tab>, and <newline> at the beginning and end of the results of the previous expansions are ignored, and any sequence of IFS characters not at the beginning or end serves to delimit words.
If IFS has a value other than the default, then sequences of the whitespace characters space and tab are ignored at the beginning and end of the word, as long as the whitespace character is in the value of IFS (an IFS whitespace character).
Any character in IFS that is not IFS whitespace, along with any adjacent IFS whitespace characters, delimits a field. A sequence of IFS whitespace characters is also treated as a delimiter. If the value of IFS is null, no word splitting occurs.

## Related

- [[ACM SIGOPS Annual Technical Conference]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[Asynchrony (computer programming)]]
- [[Attentive user interface]]
- [[Automatic mutual exclusion]]
- [[Behavior authoring]]
- [[Behavioral modeling in computer-aided design]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Input_Field_Separators