---
title: "Universe Unveiled | 寰宇揭纱"
date: 2023-09-23 00:00:00 +0800
categories: [Game Design, Projects]
tags: [Game Project]
---

## OVERVIEW
![Logo](/assets/img/GameDesign/Projects/Universe%20Unveiled/Logo.png){: w="300"}
*Logo*

### Game Concept
- Space
- Science
- Education

### Story
Players will control an alien spacecraft that arrives in the solar system, maneuvering on orbits to approach various planets to collect their knowledge. Once players gather data from each planet, they can read about the knowledge of each planet in the archive.

<!-- 玩家将操控来到太阳系的外星飞船，通过在轨道上变轨，控制自己的飞船接近各个行星以收集它们的知识。当玩家收集到每个行星的数据后，就可以在档案库中阅读到各个星球的知识。 -->

![Cool](/assets/img/GameDesign/Projects/Universe%20Unveiled/Cool.png){: w="600"}
*Screenshot from Universe Unveiled*

### Idea
This game is an educational type of science popularization game. When designing it, I defined the gameplay scenes of the game as a science and technology exhibition hall, with the target audience being those little ones who are eager to explore the universe.

I believe that learning about spaceship maneuvers between orbits and the effects of gravity on celestial bodies from books is far less effective than personally controlling a spaceship and intuitively experiencing it all. Therefore, I created this educational game.

This is a practical integration of gaming and education. Throughout the design and development of this game, I have learned a lot.

<!-- 这个游戏是一个科普教育类型的游戏，在设计它时，我将游戏的游玩场景定义为了科技展览馆，游戏的对象则是那些对宇宙充满渴望的小家伙们。

我认为在书本上学习飞船在轨道间的移动，以及万有引力对星体的作用时产生的效果，远不如亲自控制飞船，直观地感受这一切，因此我做出了这个科普游戏。

这是一次将游戏和教育结合的实践，在设计与开发这个游戏的过程中，我学到了许多。 -->

### Inspiration
The inspiration for the game comes from a series of space exploration movies, games, such as [*Interstellar*](https://www.imdb.com/title/tt0816692/), [*Outer Wilds*](https://store.steampowered.com/app/753640/Outer_Wilds/), and [*Starfield*](https://store.steampowered.com/app/1716740/Starfield/), and I myself have a lot of curiosity about the universe. At the same time, educational games often have high requirements for authenticity because they are used to present real scientific knowledge.

Combining my curiosity about the universe with the demand for authenticity in educational settings, I came up with the idea of "Players exploring the solar system." The initial gameplay of the game—where players directly control spacecraft and perform orbital transfers—aligns with this vision.

![Starfiled](https://cdn.cloudflare.steamstatic.com/steam/apps/1716740/ss_2288919a390c0147b7d2226354a61452016fd087.1920x1080.jpg?t=1704299959){: w="600"}
*Screenshot from Starfiled*

<!-- 游戏的灵感来源于星际穿越、星际拓荒、星空等一系列探索太空的影视、游戏，我自己也对宇宙有着很多的好奇。同时，教育游戏对真实性往往有着较高要求，因为它们是用来呈现真实的科学知识的。

在对宇宙的好奇和教育要求的真实性两者结合下，我产生了“玩家探索太阳系”这一想法。游戏最初期的玩法——玩家直接控制飞船，完成轨道转移也与之相符。 -->

## MY CONTRIBUTIONS
### Design
I have completed most of the design for this game, including the representation of the space environment, the connections between various scenes, game mechanics, and logic, and so on.

The atomic behaviors within the game mechanics—target selection, orbit adjustments, and flight—also involve a fundamental feedback loop. The player-controlled spaceship must fly within a certain range of planets. Controlling the spaceship is essentially a process of assessing the current situation and devising strategies accordingly. Such actions not only encourage players to consider the environment in space for better learning but also effectively exercise children's strategic thinking, learning abilities, and capacity to face challenges.

<!-- 游戏的大部分设计由我完成，包括太空环境的表现、各个场景间的连接、游戏机制和逻辑等等。

游戏机制中的原子行为——选取目标、调整轨道并飞行——也有着一套最基础的反馈循环，玩家操控的飞船必须飞入星球的一定范围内，控制飞船飞行实际上是根据现有情况判断，并产生策略的过程。这样的行为不仅仅能让玩家考虑到太空中的环境从而更好的学习，还能有效地锻炼小孩子的策略思维和学习、应对挑战的能力。 -->

### Gameplay Iteration
In the initial design, players would directly control the spacecraft, down to its rotation, orientation, and when to ignite thrusters for acceleration. However, the consequences of this approach quickly became apparent—after multiple attempts, even I couldn't complete a simple flight.

The game features a highly realistic space system, and allowing players full control over the spacecraft on such a basis undoubtedly increases the game's difficulty. Since the ultimate audience for educational games will be children, extremely difficult operations are definitely not what I want.

After rethinking the design, I have decided to simplify the spacecraft's control system. If you want a system to be less complex, you just need to simplify it upwards, incorporating more detailed operational behaviors into a concise set of controls.

In the end, after simplification, players only need to choose the orbit to fly, the insertion point, and the arc of the flight curve, with the rest being automatically handled by the system. While this approach may reduce the sense of immersion in spacecraft control, it better demonstrates the behavior of space orbital transfers. And let's never forget the game's audience: creating an educational game that any child cannot operate smoothly would undoubtedly be a huge failure.

<!-- 在最初的设计中，玩家将直接控制飞行器，细致到飞行器的旋转、朝向以及何时点火加速。这样做的结果很快就展现了出来——经过多次尝试，就连我也不能完成一次最简单的飞行。

游戏有着即为真实的太空系统，在这样的基础上让玩家完全控制飞行器，无疑是增加了游戏的难度。科普游戏最终的受众将是小孩子们，所以极难的操作绝对不是我想要的。

经过重新思考，我决定将飞行器的控制系统做出简化。如果想让一个系统不至于那么复杂，那么只需要将这个系统向上简化，用简约的操作包含更多下层的细致的操作行为。

最后，经过简化，玩家只需要选择飞行的轨道、接入点以及飞行曲线的弧度，剩下的将由系统自动完成。这样做或许会减少了飞行器控制的代入感，但更能表现出太空轨道转移的行为，并且永远不要忘记游戏的受众，做出一个任何小孩子都无法顺利操作的科普游戏无疑是极为失败的。 -->

![Transfer](/assets/img/GameDesign/Projects/Universe%20Unveiled/Transfer.png){: w="600"}
*Spacecraft Transfer*

### UI Design
I have always believed that cohesion in game design is crucial and often lacking in many games today. Nowadays, game UIs often follow standard frameworks, but I aim to integrate UI more tightly with the game itself. The style of the UI should align with the game, and it can also hint at gameplay mechanics.

In this game, the menu is designed in the style of planetary orbits, with option buttons moving along the orbit like planets. To ensure readability, I've also added an outer ring of orange halo for identification. These elements are also part of the game's mechanics.

<!-- 我一直认为游戏设计中的整体性是很重要并且也是当今很多游戏所缺失的一点。如今，游戏的UI早已有了许多固定框架，但我更想在此基础上将UI与游戏结合得更加紧密。UI的风格应与游戏保持一致，除此之外，也可以预示游戏的玩法、机制。

在这个游戏中，菜单被设计成了行星轨道的样式，具体的选项就像行星一样在轨道上移动。同时为了保证UI的可读性，我也在外层加入了一圈橙色光环用以标识。这些也同时是游戏的一部分机制。 -->

![Start](/assets/img/GameDesign/Projects/Universe%20Unveiled/Start.png){: w="600"}
*Start Screen*

## MORE DOPE PICTURES...
![GameView](/assets/img/GameDesign/Projects/Universe%20Unveiled/GameView.png){: w="600"}
*Solar System: The real scale of the Solar System is very different from what many people think.*
![Earth](/assets/img/GameDesign/Projects/Universe%20Unveiled/Earth.png){: w="600"}
*Earth: You can see the Earth! All planets have highly detailed 2K textures whenever possible.*
![Maneuver](/assets/img/GameDesign/Projects/Universe%20Unveiled/Maneuver.png){: w="600"}
*Orbit Selection: The spaceship and target planets are differentiated by blue and orange outlines. I particularly enjoy the bloom effect, as it adds a futuristic feel to the clean lines.*
![Ship](/assets/img/GameDesign/Projects/Universe%20Unveiled/Ship.png){: w="600"}
*Spaceship and Jupiter: When their orbits intersect, it signifies that the player has gathered information.*
![Archive](/assets/img/GameDesign/Projects/Universe%20Unveiled/Archive.png){: w="600"}
*Archive: Swipe left or right to view information about different planets.*
![Info](/assets/img/GameDesign/Projects/Universe%20Unveiled/Info.png){: w="600"}
*Information about Mercury: I admit that the UI here is very rudimentary; we simply didn't have the time to make it better.*

## CREDITS
- Development: 韩浩天（Me）、刘祺玉
- Special Thanks: [NASA](https://www.nasa.gov/)

> If you have any questions please feel free to contact me<br>
