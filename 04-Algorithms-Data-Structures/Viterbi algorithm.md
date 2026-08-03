---
title: "Viterbi algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Viterbi_algorithm"
wikipedia_categories: ["Dynamic programming", "Error detection and correction", "Markov models"]
related: ["[[Forward–backward algorithm]]", "[[Iterative Viterbi decoding]]", "[[Acknowledgement (data networks)]]", "[[Alternant code]]", "[[Backward induction]]", "[[Baum–Welch algorithm]]", "[[BCH code]]", "[[Bellman equation]]", "[[Bellman–Ford algorithm]]", "[[Berger code]]"]
---

# Viterbi algorithm

The Viterbi algorithm is a dynamic programming algorithm that finds the most likely sequence of hidden events that would explain a sequence of observed events. The result of the algorithm is often called the Viterbi path. It is most commonly used with hidden Markov models (HMMs). For example, if a doctor observes a patient's symptoms over several days (the observed events), the Viterbi algorithm could determine the most probable sequence of underlying health conditions (the hidden events) that caused those symptoms.
The algorithm has found universal application in decoding the convolutional codes used in both CDMA and GSM digital cellular, dial-up modems, satellite, deep-space communications, and 802.11 wireless LANs. It is also commonly used in speech recognition, speech synthesis, diarization, keyword spotting, computational linguistics, and bioinformatics. For instance, in speech-to-text (speech recognition), the acoustic signal is the observed sequence, and a string of text is the "hidden cause" of that signal. The Viterbi algorithm finds the most likely string of text given the acoustic signal.

## Related

- [[Forward–backward algorithm]]
- [[Iterative Viterbi decoding]]
- [[Acknowledgement (data networks)]]
- [[Alternant code]]
- [[Backward induction]]
- [[Baum–Welch algorithm]]
- [[BCH code]]
- [[Bellman equation]]
- [[Bellman–Ford algorithm]]
- [[Berger code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Viterbi_algorithm