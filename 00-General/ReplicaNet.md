---
title: "ReplicaNet"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/ReplicaNet"
wikipedia_categories: ["Freeware", "Middleware"]
related: ["[[ActiveVOS]]", "[[Advanced Message Queuing Protocol]]", "[[Advanced Resource Connector]]", "[[Akka.io]]", "[[Asynchrony (computer programming)]]", "[[Audiokinetic Wwise]]", "[[Ayotle]]", "[[Base One Foundation Component Library]]", "[[BonziBuddy]]", "[[Candle Corporation]]"]
---

# ReplicaNet

== Introduction ==
Distributed computing and distributed object systems are designed to allow software modules or objects to work together where the objects can be located on different computers connected by a network. Interactive computer simulations and computer games can use object-oriented programming languages such as C++ to maintain a database of entities, player characters, monsters, tanks or just about anything that can exist in a simulated world.

== How ReplicaNet works ==
Using an object description language or by programmatically registering filter classes each machine knows how to create and update each C++ class object. Each object is then treated as a potential network shareable object on the machine that allocates it. This machine has control over the C++ classes and can change variables or call member functions as normal. Once the object is ready to be shared to other machines the object is published on to the ReplicaNet network session. The underlying ReplicaNet software detects changes in the object and automatically updates the replicated classes on the machines connected to the network session. Any changes made to the member variables of the C++ classes can be extrapolated by ReplicaNet using several pre-defined filters to reduce the amount of network traffic when transmitting changes in the object.
This approach of describing objects that can then be processed by other computers is similar to other systems such as CORBA, Java remote method invocation and Distributed Component Object Model.

In 2011 Game Developer magazine announced ReplicaNet 7.0 as one of the Networking finalists for the Front Line Awards which honors the best networking middleware in the video game industry.

== Products using ReplicaNet include ==
Marathon 2: Durandal  
Virtual Interactive Combat Environment
Urban Chaos: Riot Response 
Universal Combat 
Sector 13
Airburst Extreme XBLA

== Book references to ReplicaNet ==
Game Programming in C++ Start to Finish by Erik Yuzwa http://gameprogrammingstarttofinish.wazooinc.com/
Massively Multiplayer Game Development 2 - Page 220 - Charles River Media.

== References ==

## Related

- [[ActiveVOS]]
- [[Advanced Message Queuing Protocol]]
- [[Advanced Resource Connector]]
- [[Akka.io]]
- [[Asynchrony (computer programming)]]
- [[Audiokinetic Wwise]]
- [[Ayotle]]
- [[Base One Foundation Component Library]]
- [[BonziBuddy]]
- [[Candle Corporation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ReplicaNet