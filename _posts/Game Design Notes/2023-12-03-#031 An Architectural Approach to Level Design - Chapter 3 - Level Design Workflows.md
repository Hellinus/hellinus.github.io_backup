---
title: "#031 An Architectural Approach to Level Design - Chapter 3 - Level Design Workflows"
date: 2023-12-03 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Level]
---

This chapter is about:
1. The methods that professional level designers use in their work and how methods from architecture can inform them.
2. Also how level design fits into the production of overall games and how to choose which content to develop first.

## FORM FOLLOWS FUNCTION
The best level designers work with a specific experiential goal in mind.

> “experience is key” - Valve level designer Dario Casali

This section is all about planning: taking experiential ideas and translating them into gameplay.

### Form Follows Core Mechanics
When designing levels, having a core mechanic idea in mind is necessary.

While many new designers assume that individual levels should simply follow the core mechanic of the game, it is possible to define **level core mechanics** to make each unique.
- Sample: TF2 Payload mode

This changes not only the mechanics of gameplay, but also the conditions of the level’s **spatial geometry** - **measurement**.

Layouts can also be based on the character’s own mechanics, the gameplay actions that form the range of possibilities for how a character may act or interact with his or her environment.
- Sample: shelter in stealth game

### Level Progression with Scaffolding Mechanisms
In each level of New Super Mario Bros. U, the central mechanism is introduced early and in a safe way—away from pits or enemies—so players can learn how to use it.

Educators call this *scaffolding*: introducing a concept and applying it in increasingly complex ways over the course of several exercises.
> As Mario U levels progress, their core mechanism is used in increasingly novel and dangerous ways (above a small platform, then above lava, then above lava with enemies).

Scaffolding can also be applied across many different gameplay genres.
> DOOM 2016: When a new monster is introduced, you see it in a cutscene then face it alone or alongside much weaker monsters. Afterward, you face the monster alongside strong monsters or in new (often disadvantageous for the player) spatial conditions: narrower pathways or alongside hazards. Once you receive a weapon that makes the monster easier, a new monster is introduced that challenges these new powers.

It is the job of the level designer to create levels that give players a space to best utilize their characters’ movement capabilities or to showcase mechanisms external to the player character.

**Remember: Make a core mechanic or mechanism the key to each level you create, and also the progression.**

## LEVEL DESIGN WORKFLOWS
By discussing several methods that take a level from “sketched idea” to implementation, we will see how functional game mechanics 
can be turned into engaging gamespaces.

### Level Design Parti
The key to a level designer’s parti is to sketch *gameplay ideas as spatial diagrams*.

Once a designer has created environmental mechanisms, that is, interactive parts of a level that factor into gameplay, they should be **usable** in many different ways in order to be valuable.

### "Scenes" and Readability
A scene is a single screen’s worth of designed level space that is currently confronting a player.
> “the most basic unit of pacing in a game”

- For 2D game, the concept of “scenes” was vital: designers could work with a limited scope of making one screen as mechanic-rich as it could be.
- For 3D game, scenes could be longer, continuous levels, so theoretically taking the approach to 3D could include making each architectural space interesting.

> One scene in *Horizon Zero Dawn* focus on observing a space from a specific angle, often an entrance or approach, readability features many of the elements that make for good scenes.
>
> Successful design for this room meant two things: 
> 1. the first was that navigating and battling enemies in the room would be interesting.
> 2. The second was that the player could see their goal, see the possible paths they could take to it, and plan how they would deal with enemies from a vantage point as they entered.
>
> Things could be different in multiplayer game.

A lot of what makes scenes work is that they address very core questions about how a level will feel to a player and what type of experience it creates.

### Non-Digital Prototypes
This section is about how **early-stage level design ideas** might be tested with non-digital prototypes.

Non-digital prototypes can define gamespaces on both the macro (large, zoomed out) and the micro (small, close-up) scale.
- As a demonstration of the game environment on a macro level, it allows players to play with the linear progression of general gameplay situations but not dig deeply into each one.
- Prototype that focuses on micro-level gameplay-prototyping could allow designers to explore issues such as enemy movement and character interaction.

### Digital Prototypes with Grayboxing
*Grayboxing* is when a level designer creates a level out of simple geometry, most often gray or quickly textured blocks (thus the name), to test whether levels accomplish the gameplay goals he or she wants.
- Grayboxing can help determine what gameplay measurements should be: Designers can draft the spatial characteristics of their levels in a parti-like way, testing the sizes and shapes of certain environments for different gameplay experiences, before specific environmental art is added to a level.

As an iterative process, grayboxing has designers begin with almost parti-like interactive forms before transitioning toward more art and ornament-centric design once gameplay for the level has been refined.

### Pacing Your Levels with the Nintendo Power Method
*Pacing* is based on the concept that in order for gameplay action to seem exciting, it must be contrasted with moments of “quieter” gameplay.
> Spatial contrast is very important for building meaningful experiences in both games and architecture. Proper pacing would have gameplay points separated from one another by periods of quieter gameplay.

> *Nintendo Power* was a game strategy and news magazine published by Nintendo beginning in the late 1980s. For many games, *Nintendo Power* would publish detailed maps of levels with caption balloons that would highlight particularly noteworthy or difficult points of gameplay.

When designing levels, utilize the same mindset by treating level drawings as ones from *Nintendo Power*, creating the overall scope of a level on a **macro-scale** and **evenly spreading** out micro-scaled areas of more intense gameplay across the entire map.

In-between the “loud” gameplay moments should be **circulation space**—spaces for movementbased gameplay, movement-based obstacles, exploration, or even rest and recharging of the player character.

### Iterative Design with Playtesting
To understand whether the experience you intend happens in your game levels, it is important to watch others play your game in both non-digital and digital forms, depending on your stage of development.

As you watch people play your levels, keep these things in mind:
- **Do they understand how to play the level?** May need a better or more transparent introduction to the mechanic before reaching the iteration of it that he or she is stuck on.
- **Is the level too hard for the player?**  Should perhaps place that challenge later in the game or build easier levels and put them before the challenge the player is stuck on.
- **Do not interfere with their play.** If he or she cannot figure it out, you should add more teaching moments to your levels.
- **Embrace happy accidents.** Evaluate whether it is game-breaking. If it is not, but could instead be an interesting secret to find, leave it in.
- **Playtest for the current stage of development.** Lead playtesters to give you feedback on issues that match your stage in development. Ask playtesters prepared questions relating to the information you want from them or create a paper survey for them to fill out.
- **Ask for additional comments, but stick to your guns.** Learn to properly vet these statements for things that can help in that stage of development versus the ones that will break your game’s core vision. Also learn to dismiss bad ideas in a friendly and non-condescending way.
- **If the player does not understand something, it is not clear enough.** No matter whether you have put in a bright neon sign, a particle effect, a sound effect, or any other gizmo that is supposed to draw player attention to an in-game event, you usually need to add at least two more before players actually perceive the event.
- **Playtest to learn what players will need to learn about your game.** Pay extra attention to the mechanics that players do and do not need help understanding. Playtesting helps you form a “lesson plan” for your game’s tutorials so that you can best respond to player needs.

As playtesters try your levels throughout your process, **document** what went well with each prototype and what could be changed or improved. Change your design and have someone playtest your next prototype. 

As you iterate, your needs will change: where you once needed playtests to explore large-scale design questions, you eventually need them to polish individual moments of gameplay. At this latter stage, you will need to understand a player’s relationship to individual pieces of level geometry and swap out what doesn’t work.

### Modular Level Design
*Modular*: premade parts that can be copied, assembled, disassembled, and moved easily.

- Creating modular assets can also aid the metric-based measurement methods.

Architects track modular elements of their buildings through documents called *building schedules*. In game art direction, it is common to utilize style guides—documents that establish color, graphics, measurement, and other artistic standards—for maintaining graphic consistency within a team.

## LEVEL DESIGN SCHEDULING
**"Which level to make first".**

### The Toy Box
A common place to start level-designing is not a level at all, but a place to build and try level mechanisms.

- mechanisms
- camera
- ...

### Building from the Middle
It may not seem intuitive at first, but many studios start designing levels somewhere in the middle of the game and save their first levels—where players will learn how to play the game—for last: trailer.

Try to find the difficulties and the order of the levels by playtesting.

### Building in Order
In action games where gameplay mechanics have to be introduced along a difficulty curve, or games with a lot of complexity, building from the middle makes a lot of sense.

However, if a game is simpler or has other methods for planning level order, designing from the first level and working in order has a lot of advantages.

- Building in order works well for Metroidvanias or other games where a strong linear element (such as a story) is central to the game’s enjoyment.
- Another reason to build your levels in order is that your game may be simple enough that you do not need to plan extensive teaching levels.

## SUMMARY
Player-centric design is key to these workflows, and seeing our levels as a series of scenes helps us clearly communicate with players.
