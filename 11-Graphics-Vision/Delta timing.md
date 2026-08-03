---
title: "Delta timing"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Delta_timing"
wikipedia_categories: ["Graphics", "Video game development"]
related: ["[[2.5D]]", "[[2022–2026 video game industry layoffs]]", "[[AAA (video game industry)]]", "[[AbleGamers]]", "[[Academy of Interactive Arts & Sciences]]", "[[Amazon Lumberyard]]", "[[Artificial intelligence in video games]]", "[[Asset flip]]", "[[Atari 2600 homebrew]]", "[[Australian Game Developers Conference]]"]
---

# Delta timing

Delta time or delta timing is a concept used by programmers in relation to hardware and network responsiveness. In graphics programming, the term is usually used for variably updating scenery based on the elapsed time since the program last updated (i.e. the previous "frame"), which will vary depending on the speed of the computer, and how much work needs to be done in the program at any given time.  This also allows graphics to be calculated separately if graphics are being multi-threaded.
In network programming, due to the unpredictable nature of internet connections, delta timing is used in a similar way to variably update the movement information received via the computer network, regardless of how long it took to receive the next data packet of movement information.
It is often done by calling a timer every frame per second that holds the time between now and last call. Thereafter the resulting number (delta time) is used to calculate how far, for instance, a video game character would have travelled during that time.  This results in the character taking the same amount of real world time to move across the screen regardless of the rate of update, and whether the delay is caused by lack of processing power or a slow internet connection.
In graphics programming, this avoids the gameplay slowing down or speeding up depending on the complexity of what is happening at any given time, which would make for an inconsistent, jarring experience (e.g. time slowing down the more characters walk onto the screen, or running too fast because only one character is on screen).  In network programming, this keeps the game world of each computer in sync with the others, by making sure each client eventually sees the same activity at the same time, even if more time has passed since the last update for some clients than others.
Big enough delays will eventually negatively affect the gameplay experience, but using Delta Time keeps the gameplay consistent so long as the computer and internet connection meet the minimum hardware requirements of the game.

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

- Wikipedia: https://en.wikipedia.org/wiki/Delta_timing