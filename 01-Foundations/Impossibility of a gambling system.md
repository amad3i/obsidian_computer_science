---
title: "Impossibility of a gambling system"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Impossibility_of_a_gambling_system"
wikipedia_categories: ["Probability theory"]
related: ["[[Additive process]]", "[[Additive smoothing]]", "[[Almost surely]]", "[[Asymptotic geometry]]", "[[Big O in probability notation]]", "[[Blackwell-Girshick equation]]", "[[Blumenthal's zero–one law]]", "[[Brownian motion and Riemann zeta function]]", "[[Carleman's condition]]", "[[Carré du champ operator]]"]
---

# Impossibility of a gambling system

The principle of the impossibility of a gambling system is a concept in probability. It states that in a random sequence, the methodical selection of subsequences does not change the probability of specific elements. The first mathematical demonstration is attributed to Richard von Mises (who used the term collective rather than sequence).
The principle states that no method for forming a subsequence of a random sequence (the gambling system) improves the odds for a specific event. For instance, a sequence of fair coin tosses produces equal and independent 50/50 chances for heads and tails.  A simple system of betting on heads every 3rd, 7th, or 21st toss, etc., does not change the odds of winning in the long run.  As a mathematical consequence of computability theory, more complicated betting strategies (such as a martingale) also cannot alter the odds in the long run.
Von Mises' mathematical demonstration defines an infinite sequence of zeros and ones as a random sequence if it is not biased by having the frequency stability property.  With this property, the frequency of zeroes in the sequence stabilizes at 1/2, and every possible subsequence selected by any systematic method is likewise not biased.
The subsequence selection criterion is important, because although the sequence 0101010101... is not biased, selecting the odd positions results in 000000... which is not random. Von Mises did not fully define  what constituted a "proper" selection rule for subsequences, but in 1940 Alonzo Church defined it as any recursive function which having read the first N elements of the sequence decides if it wants to select element number N+1. Church was a pioneer in the field of computable functions, and the definition he made relied on the Church Turing Thesis for computability.
In the mid-1960s, A. N. Kolmogorov and D. W. Loveland independently proposed a more permissive selection rule. In their view Church's recursive function definition was too restrictive in that it read the elements in order. Instead they proposed a rule based on a partially computable process which having read any N elements of the sequence, decides if it wants to select another element which has not been read yet.
The principle influenced modern concepts in randomness, e.g. the work by A. N. Kolmogorov in considering a finite sequence random (with respect to a class of computing systems) if any program that can generate the sequence is at least as long as the sequence itself.

## Related

- [[Additive process]]
- [[Additive smoothing]]
- [[Almost surely]]
- [[Asymptotic geometry]]
- [[Big O in probability notation]]
- [[Blackwell-Girshick equation]]
- [[Blumenthal's zero–one law]]
- [[Brownian motion and Riemann zeta function]]
- [[Carleman's condition]]
- [[Carré du champ operator]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Impossibility_of_a_gambling_system