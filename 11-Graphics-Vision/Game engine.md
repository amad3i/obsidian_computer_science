---
title: "Game engine"
tags: ["cs", "graphics-vision", "core"]
domain: Graphics & Vision
level: core
source: "https://en.wikipedia.org/wiki/Game_engine"
wikipedia_categories: ["Video game development", "Video game engines"]
related: ["[[Amazon Lumberyard]]", "[[Decima (game engine)]]", "[[OpenXR]]", "[[Unigine]]", "[[Virtually Live]]", "[[2.5D]]", "[[2022–2026 video game industry layoffs]]", "[[AAA (video game industry)]]", "[[AbleGamers]]", "[[Academy of Interactive Arts & Sciences]]"]
---

# Game engine

A game engine is a software framework primarily designed for video game development, which may include specialized software libraries and packages, such as level editors. The term "engine" is a direct analogue of "software engine", having it employed across sectors of the software industry.
Furthermore, game engine  may also refer to the integrated development environment as an interface behind the given framework, typically a suite of visual development tools and features for developing video games.
Game developers can use game engines to create and publish video games across platforms, such as desktops, mobile devices, video game consoles, and other types of computers. The core functionalities commonly covered by a game engine are a 2D or 3D renderer, physics engine, audio engine, scripting, animation, artificial intelligence, networking, streaming, memory management, threads, localization support, scene graph, and cinematics. Game engine developers often economize game development through reuse or adaptation of abstractions built into game engines for production of various games, or through porting of videogames from a single to other target platforms.

== Purpose ==

In many cases, game engines provide a suite of visual development tools in addition to reusable software components. These tools are generally provided in an integrated development environment to enable simplified, rapid development of games in a data-driven manner. Game-engine developers often attempt to preempt implementer needs by developing robust software suites, which include many elements a game developer may need to build a game. Most game-engine suites provide facilities that ease development, such as graphics, sound, physics and artificial intelligence (AI) functions. These game engines are sometimes called "middleware" because, as with the business sense of the term, they provide a flexible and reusable software platform which provides all the core functionality needed, right out of the box, to develop a game application while reducing costs, complexities, and time-to-market—all critical factors in the highly competitive video game industry.
Like other types of middleware, game engines usually provide platform abstraction, allowing the same game to run on various platforms (including game consoles and personal computers) with few, if any, changes made to the game source code. Often, programmers design game engines with a component-based architecture that allows specific systems in the engine to be replaced or extended with more specialized (and often more expensive) game-middleware components. Some game engines comprise a series of loosely-connected game middleware components that can be selectively combined to create a custom engine, instead of the more common approach of extending or customizing a flexible integrated product. However achieved, extensibility remains a high priority for game engines due to the wide variety of uses for which they are applied. Despite the specificity of the name "game engine", end users often re-purpose game engines for other kinds of interactive applications with real-time graphical requirements—such as marketing demos, architectural visualizations, training simulations, and modeling environments.
Some game engines only provide real-time 3D rendering capabilities instead of the wide range of functionality needed by games. These engines rely upon the game developer to implement the rest of this functionality or to assemble it from other game-middleware components. These types of engines are generally referred to as a "graphics engine", "rendering engine", or "3D engine" instead of the all-encompassing term "game engine". This terminology is inconsistently used, as many full-featured 3D game engines are simply referred to as "3D engines". Examples of graphics engines include: Crystal Space, Genesis3D, Irrlicht, OGRE, RealmForge, Truevision3D, and Vision Engine. Modern game- or graphics-engines generally provide a scene graph—an object-oriented representation of the 3D game-world which often simplifies game design and can be used for more efficient rendering of vast virtual worlds. Most game engines or graphics engines use a Graphics API, which eases communication with the GPU. But older games did not have hardware acceleration or GPUs and had to build their own software renderer.
As technology ages, the components of an engine may become obsolete or insufficient for the requirements of a given project. Since the complexity of programming an entirely new engine may result in unwanted delays (or necessitate that a project restart from the beginning), an engine-development team may elect to update their existing engine with newer functionality or components.
Game engines are not limited to use in the video game field, and have found uses in other scientific fields. Part of this is due to game engines being optimized for consumer-grade computing equipment rather than high-performance computing, allowing researchers to develop programs for their use on lower cost machines. Game engines also simplify many of the computing operations needed for scientific software, including graphics, networking, and interactivity, reducing the need to develop these features themselves.

== History ==

Before game engines, games were typically written as singular entities: a game for the Atari 2600, for example, had to be designed from the bottom up to make optimal use of the display hardware—this core display routine is now called the kernel by developers of games for older systems. Other platforms had more leeway, but even when display was not a concern, memory constraints usually sabotaged attempts to create the data-heavy design that an engine needs. Even on more accommodating platforms, very little could be reused between games. The rapid advance of arcade hardware—which was the leading edge of the market at the time—meant that most of the code would have to be thrown out afterwards anyway, as later generations of games would use completely different game designs that took advantage of extra resources. Thus, most game designs through the 1980s were designed through a hard-coded rule set with a small number of levels and graphics data. Since the golden age of arcade video games, it became common for video game companies to develop in-house game engines for use with first-party software.
A notable example of an in-house game engine on home consoles in the mid-1980s was the smooth side-scrolling engine developed by Shigeru Miyamoto's team at Nintendo for the Nintendo Entertainment System (NES). The engine they had developed for the side-scrolling racing game Excitebike (1984) was later employed for the scrolling platformer Super Mario Bros. (1985). This allowed Mario to smoothly accelerate from a walk to a run, rather than move at a constant speed like in earlier platformers.
While third-party game engines were not common until the rise of 3D computer graphics in the 1990s, several 2D game creation systems were produced in the 1980s for independent video game development. These include Pinball Construction Set (1983), ASCII's War Game Construction Kit (1983), Thunder Force Construction (1984), Adventure Construction Set (1984), Garry Kitchen's GameMaker (1985), Wargame Construction Set (1986), Shoot-'Em-Up Construction Kit (1987), Arcade Game Construction Kit (1988), and, most popularly, ASCII's RPG Maker engines from 1998 onward. Klik & Play (1994) is another legacy offering that is still available.
The term game engine emerged in the mid-1990s, particularly with the rise of 3D games like first-person shooters, which often featured a dedicated first-person shooter engine. For instance, Epic Games, founded by Tim Sweeney, debuted its Unreal Engine in 1998.
Such was the popularity of Id Software's Doom and Quake games: rather than building from scratch, its developers licensed the core portions of the software and designed their own graphics, characters, weapons, and levels—they were the "game content" or "game assets." Separation of game-specific rules and data from basic concepts like collision detection and game entity meant that teams could grow and specialize.
Later games, such as id Software's Quake III Arena and Epic Games' Unreal (1998), were designed with this approach in mind, with the engine and content developed separately. The practice of licensing such technology has proved to be a useful auxiliary revenue stream for some game developers, as a single license for a high-end commercial game engine can range from $10,000 to millions of dollars, and the number of licensees can reach several dozen companies, as seen with the Unreal Engine. At the very least, reusable engines make developing game sequels faster and easier, which is a valuable advantage in the competitive video game industry. While a strong rivalry existed between Epic Games and id Software around 2000, Epic Game's Unreal Engine has since become far more popular than

*(note truncated for size; full article at the source link below)*

## Related

- [[Amazon Lumberyard]]
- [[Decima (game engine)]]
- [[OpenXR]]
- [[Unigine]]
- [[Virtually Live]]
- [[2.5D]]
- [[2022–2026 video game industry layoffs]]
- [[AAA (video game industry)]]
- [[AbleGamers]]
- [[Academy of Interactive Arts & Sciences]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Game_engine