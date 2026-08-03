---
title: "Presentation logic"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Presentation_logic"
wikipedia_categories: ["Software architecture", "Software design", "Software engineering stubs", "Software engineering terminology"]
related: ["[[Multitier architecture]]", "[[User onboarding]]", "[[Active reviews for intermediate designs]]", "[[Ambiguous viewpoint]]", "[[Architecture astronaut]]", "[[Common Component Architecture]]", "[[Connection broker]]", "[[Darwin (ADL)]]", "[[Domain-driven design]]", "[[Event storming]]"]
---

# Presentation logic

In software development, presentation logic is concerned with how business objects are displayed to users of the software, e.g. the choice between a pop-up screen and a drop-down menu. The separation of business logic from presentation logic is an important concern for software development and an instance of the separation of content and presentation.
One major rationale behind "effective separation" is the need for maximum flexibility in the code and resources dedicated to the presentation logic. Client demands, changing customer preferences and desire to present a "fresh face" for pre-existing content often result in the need to dramatically modify the public appearance of content while disrupting the underlying infrastructure as little as possible.
The distinction between "presentation" (front end) and "business logic" is usually an important one, because:

the presentation source code language may differ from other code assets;
the production process for the application may require the work to be done at separate times and locations;
different workers have different skill sets, and presentation skills do not always coincide with skills for coding business logic;
code assets are easier to maintain and more readable when disparate components are kept separate and loosely coupled;

## Related

- [[Multitier architecture]]
- [[User onboarding]]
- [[Active reviews for intermediate designs]]
- [[Ambiguous viewpoint]]
- [[Architecture astronaut]]
- [[Common Component Architecture]]
- [[Connection broker]]
- [[Darwin (ADL)]]
- [[Domain-driven design]]
- [[Event storming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Presentation_logic