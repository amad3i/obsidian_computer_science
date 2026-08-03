---
title: "Vicious circle principle"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Vicious_circle_principle"
wikipedia_categories: ["Concepts in logic", "Philosophical logic", "Principles", "Set theory"]
related: ["[[Extension (semantics)]]", "[[Extensionality]]", "[[Hume's principle]]", "[[Inhabited set]]", "[[Primitive notion]]", "[[Set (mathematics)]]", "[[Term logic]]", "[[Absoluteness (logic)]]", "[[Admissible set]]", "[[Agentive logic]]"]
---

# Vicious circle principle

The vicious circle principle is a principle that was endorsed by many predicativist mathematicians in the early 20th century to prevent contradictions.  The principle states that no object or property may be introduced by a definition that depends on that object or property itself.  In addition to ruling out definitions that are explicitly circular (like "an object has property P iff it is not next to anything that has property P"), this principle rules out definitions that quantify over domains which include the entity being defined.  Thus, it blocks Russell's paradox, which defines a set R that contains all sets which do not contain themselves.  This definition is blocked because it defines a new set in terms of the totality of all sets, of which this new set would itself be a member.
However, it also blocks one standard definition of the natural numbers.  First, we define a property as being "hereditary" if, whenever a number n has the property, so does n +1.  Then we say that x has the property of being a natural number if and only if it has every hereditary property that 0 has.  This definition is blocked, because it defines "natural number" in terms of the totality of all hereditary properties, but "natural number" itself would be such a hereditary property, so the definition is circular in this sense.
Most modern mathematicians and philosophers of mathematics think that this particular definition is not circular in any problematic sense, and thus they reject the vicious circle principle.  But it was endorsed by many early 20th-century researchers, including Bertrand Russell and Henri Poincaré.  On the other hand, Frank P. Ramsey and Rudolf Carnap accepted the ban on explicit circularity, but argued against the ban on circular quantification.  After all, the definition "let T be the tallest man in the room" defines T by means of quantification over a domain (men in the room) of which T is a member.  But this is not problematic, they suggest, because the definition does not actually create the person, but merely shows how to pick him out of the totality.  Similarly, they suggest, definitions do not actually create sets or properties or objects, but rather just give one way of picking out the already existing entity from the collection of which it is a part.  Thus, this sort of circularity in terms of quantification cannot cause any problems.
This principle was the reason for Russell's development of the ramified theory of types rather than the theory of simple types.  (See "Ramified Hierarchy and Impredicative Principles".)

An analysis of the paradoxes to be avoided shows that they all result from a kind of vicious circle. The vicious circles in question arise from supposing that a collection of objects may contain members which can only be defined by means of the collection as a whole. Thus, for example, the collection of propositions will be supposed to contain a proposition stating that “all propositions are either true or false.” It would seem, however, that such a statement could not be legitimate unless “all propositions” referred to some already definite collection, which it cannot do if new propositions are created by statements about “all propositions.” We shall, therefore, have to say that statements about “all propositions” are meaningless.… The principle which enables us to avoid illegitimate totalities may be stated as follows: “Whatever involves all of a collection must not be one of the collection”; or, conversely: “If, provided a certain collection had a total, it would have members only definable in terms of that total, then the said collection has no total.” We shall call this the “vicious-circle principle,” because it enables us to avoid the vicious circles involved in the assumption of illegitimate totalities. (Whitehead and Russell 1910, 37) (quoted in the Stanford Encyclopedia of Philosophy entry on Russell's Paradox)

## Related

- [[Extension (semantics)]]
- [[Extensionality]]
- [[Hume's principle]]
- [[Inhabited set]]
- [[Primitive notion]]
- [[Set (mathematics)]]
- [[Term logic]]
- [[Absoluteness (logic)]]
- [[Admissible set]]
- [[Agentive logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vicious_circle_principle