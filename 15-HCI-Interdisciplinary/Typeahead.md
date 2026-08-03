---
title: "Typeahead"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Typeahead"
wikipedia_categories: ["Typing", "User interface techniques"]
related: ["[[3D human–computer interaction]]", "[[Accelerator table]]", "[[Alt-Tab]]", "[[Application posture]]", "[[Attentive user interface]]", "[[Audification]]", "[[Auditory display]]", "[[Augmented reality]]", "[[Bounce keys]]", "[[Bracket matching]]"]
---

# Typeahead

Typeahead is a feature of computers and software (and some typewriters) that enables users to continue typing regardless of program or computer operation—the user may type in whatever speed is desired, and if the receiving software is busy at the time it will be called to handle this later. Often this means that keystrokes entered will not be displayed on the screen immediately. This programming technique for handling uses what is known as a keyboard buffer.
Typeahead has its roots in the age of typewriters. The IBM Selectric typewriter, first released in 1961, had a mechanical key lockout feature designed to smooth out typists' irregular keystrokes that, to many users, felt like typeahead.
Achieving true typeahead requires maintaining a so-called "typeahead buffer"—a FIFO queue, for instance—whose role it is to store a limited amount of keyboard input until it is called for. Installing such a buffer can be done at both the hardware and the software levels; most modern operating systems, such as Unix, implement this using software, calling kernel interrupts.
In some network operations, one might attempt to dispatch information over a network, regardless whether the receiving program manages to keep up, using the recipient's typeahead functions. However, as this is far too reliant on the specifications of the computer with which one is communicating, it is not often used.

## Related

- [[3D human–computer interaction]]
- [[Accelerator table]]
- [[Alt-Tab]]
- [[Application posture]]
- [[Attentive user interface]]
- [[Audification]]
- [[Auditory display]]
- [[Augmented reality]]
- [[Bounce keys]]
- [[Bracket matching]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Typeahead