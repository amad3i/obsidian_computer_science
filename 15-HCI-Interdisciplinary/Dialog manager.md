---
title: "Dialog manager"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Dialog_manager"
wikipedia_categories: ["Human–computer interaction"]
related: ["[[10-foot user interface]]", "[[3D human–computer interaction]]", "[[3Dconnexion]]", "[[Aaron Marcus]]", "[[ACM Symposium on User Interface Software and Technology]]", "[[ACM-IEEE Virtual Reality International Conference]]", "[[Activity recognition]]", "[[Adaptation (computer science)]]", "[[Addiction by Design]]", "[[Aesthetic–usability effect]]"]
---

# Dialog manager

A dialog manager (DM) is a component of a dialog system (DS), responsible for the state and flow of the conversation. Usually:

The input to the DM is the human utterance, usually converted to some system-specific semantic representation by the Natural language understanding (NLU) component. For example, in a flight-planning dialog system, the input may look like "ORDER(from=TA,to=JER,date=2012-01-01)".
The DM usually maintains some state variables, such as the dialog history, the latest unanswered question, etc., depending on the system.
The output of the DM is a list of instructions to other parts of the dialog system, usually in a semantic representation, for example "TELL(flight-num=123,flight-time=12:34)". This semantic representation is usually converted to human language by the Natural language generation (NLG) component.
There are many different DMs that fulfill very different roles. There can even be several DM components in a single DS.
The only thing common to all DMs is that they are stateful, in contrast to other parts of the DS (such as the NLU and NLG components), which are just stateless functions. The DM roles can roughly be divided into these groups:

Input-control, which enable context-dependent processing of the human utterances.
Output-control, which enable state-dependent generation of text.
Strategic flow-control, which decide what action the dialog agent should take at each point of the dialog.
Tactic flow-control, which make some tactical conversational decisions (error handling, initiative control, etc.).

## Related

- [[10-foot user interface]]
- [[3D human–computer interaction]]
- [[3Dconnexion]]
- [[Aaron Marcus]]
- [[ACM Symposium on User Interface Software and Technology]]
- [[ACM-IEEE Virtual Reality International Conference]]
- [[Activity recognition]]
- [[Adaptation (computer science)]]
- [[Addiction by Design]]
- [[Aesthetic–usability effect]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dialog_manager