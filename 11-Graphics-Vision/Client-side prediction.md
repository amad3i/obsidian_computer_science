---
title: "Client-side prediction"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Client-side_prediction"
wikipedia_categories: ["Video game development"]
related: ["[[2.5D]]", "[[2022–2026 video game industry layoffs]]", "[[AAA (video game industry)]]", "[[AbleGamers]]", "[[Academy of Interactive Arts & Sciences]]", "[[Amazon Lumberyard]]", "[[Artificial intelligence in video games]]", "[[Asset flip]]", "[[Atari 2600 homebrew]]", "[[Australian Game Developers Conference]]"]
---

# Client-side prediction

Client-side prediction is a network programming technique used in video games intended to conceal negative effects of high latency connections. The technique attempts to make the player's input feel more instantaneous while governing the player's actions on a remote server.
The process of client-side prediction refers to having the client locally react to user input before the server has acknowledged the input and updated the game state. So, instead of the client only sending control input to the server and waiting for an updated game state in return, the client also, in parallel with this, predicts the game state locally, and gives the user feedback without awaiting an updated game state from the server.
Client-side prediction reduces latency problems, since there no longer will be a delay between input and client-side visual feedback due to network ping times. However, it also introduces a desynchronization of the client and server game states, which needs to be handled to keep the game playable. Usually, the desync is corrected when the client receives the updated game state, but as instantaneous correction would lead to "snapping", there are usually some "smoothing" algorithms involved.  For example, one common smoothing algorithm would be to check each visible object's client-side location to see if it is within some error epsilon of its server-side location.  If not, the client-side's information is updated to the server-side directly (snapped because of too much desynchronization).  However, if the client-side location is not too far, a new position between the client-side and server-side is interpolated; this position is set to be within some small step delta from the client-side location, which is generally judged to be "small enough" to be unintrusive to the user.
Another solution to the desynchronization issue, commonly used in conjunction with client-side prediction, is called server reconciliation. The client includes a sequence number in every input sent to the server, and keeps a local copy. When the server sends an authoritative update to a client, it includes the sequence number of the last processed input for that client. The client accepts the new state, and reapplies the inputs not yet processed by the server, completely eliminating visible desynchronization issues in most cases.
The earliest known first-person shooter to use client-side prediction is Duke Nukem 3D, which had it built-in since the January 29, 1996 shareware release. The technique was also a prominent feature of QuakeWorld, the popular add-on to Quake. While network play was included in the original Quake game, it was optimized mainly for LAN play. Having had high-speed home connections (a rarity at the time), Quake's designers overlooked their assumptions of high bandwidth and low ping times that made playing online frustrating for dial-up users. After a series of experiments in a long private beta, id Software released QuakeWorld with a new predictive model that proved popular with both high and low latency players.

## Related

- [[2.5D]]
- [[2022–2026 video game industry layoffs]]
- [[AAA (video game industry)]]
- [[AbleGamers]]
- [[Academy of Interactive Arts & Sciences]]
- [[Amazon Lumberyard]]
- [[Artificial intelligence in video games]]
- [[Asset flip]]
- [[Atari 2600 homebrew]]
- [[Australian Game Developers Conference]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Client-side_prediction