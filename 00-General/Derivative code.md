---
title: "Derivative code"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Derivative_code"
wikipedia_categories: ["Computer programming", "Computer science stubs"]
related: ["[[Asynchrony (computer programming)]]", "[[Services computing]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Algorave]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[Asynchronous procedure call]]", "[[Attentive user interface]]", "[[Automatic mutual exclusion]]"]
---

# Derivative code

Derivative code or Chameleon code is source code which has been derived entirely from one or more other machine readable file formats.  If recursive transcompiling is used in the development process, some code will survive all the way through the pipeline from beginning to end, and then back to the beginning again.
This code is, by definition, derivative code.  The following procedure can be used to easily test if any source code is derivative code or not.  

Delete the code in question
Build (or compile) the project
If the build process simply replaces the source code which has been deleted, it is (obviously) code which has been derived from something else and is therefore, by definition, derivative code.
If the build process fails, and a human needs to re-create the deleted code by hand, this is again, by definition, hand code.
The transcompilers and other tools which create derivative code, are usually themselves either in part, or entirely hand code.

## Related

- [[Asynchrony (computer programming)]]
- [[Services computing]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Algorave]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[Asynchronous procedure call]]
- [[Attentive user interface]]
- [[Automatic mutual exclusion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Derivative_code