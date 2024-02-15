---
title: "#024 Level Design - Process - Combat"
date: 2023-09-20 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Level]
---

> Designing physical conflict between player(s) and/or NPCs.<br>
> From [The Level Design Book](https://book.leveldesignbook.com/).

## What is combat design?
**Combat design** is about making game systems for physical conflict between player(s) and often AI-controlled enemies too.

In level design, we generally assume this is combat for a first person shooter or other real-time 3D action game. This book will also make that assumption.

Note that competitive **player vs. player (PvP)** functions very differently from single player / cooperative **player vs. enemy (PvE)** combat. PvP usually implies a fair chance to win for all combatants. In contrast, PvE provides delayed but guaranteed victory. These are two very different promises to make to players, and so the level design is different too.

## Combat systems
When making a combat game, you have two options:
- Mod an existing combat game.
- Build your own combat gameplay from scratch.

You cannot make good combat levels without good combat systems. But developing this core combat toolkit requires a lot of code, art, animation, audio, and tuning. 

This is a complex topic that is outside the scope of a level design book. Asking "how do I make good combat?" is like asking "how do I make a good game?" It's a big question.

This is why we strongly suggest modding: that way, you can reuse a game's already-proven core combat systems without having to build your own.

That said, even if you do mod an existing combat game, you still have to be able to theorize how it works. All single player and multiplayer combat games have some form of these core elements:
- Combat mechanics
- Weapon design
- Economy

In a big commercial studio with specialized development roles, **none of those core combat elements would be the level designer's responsibility.** However, a level designer cannot make levels without understanding them.

### Combat mechanics
**Combat mechanics** are the player's repeated actions / skills / weapons used to fight enemies. Some common combat mechanics:**
- **Move** away from danger, control **territory**
- **Aim** at specific enemy types / weak points
- **Timing** an attack for a **tell / telegraph** (opportunity)
- Chain attacks into **combos,** combine actions or weapons
- **Block** an enemy attack; **parry / counter / evade** at the right time
- Use **traps** like explosive barrels, water, lava, cliffs, etc

### Weapon design
Many games provide the player with multiple weapons to use. **Weapon design** is about conceptualizing, implementing, and balancing this arsenal. Some aspects to consider:
- **Weapon feel and fantasy** (e.g. big slow gun vs. sneaky knife vs. loud chainsaw)
- **Stats** like varied damage, range, rate of fire, ammo supply
    - For guns: varied spread, recoil, sights, penetration, magazine size, reload speed
- **Situational awareness** to pick the most appropriate / effective weapon

### Economy
**Economy** is a general game design term for the overall system of costs / benefits / rewards that the player must consider throughout the game. The player's access to resources affects which mechanics and weapons they use and when:
- **Weapon economy:** ammo, time (DPS), arsenal / loadout
    - example: the player has 1 rocket left, so they save it until they fight a strong enemy that is weak to rockets
    - example: the player has only 15 seconds of oxygen underwater, so they need a high DPS weapon to fight an underwater enemy
- **Player state:** short term economy like health, inventory, consumables
    - example: the player has 99% health, so they will avoid a health item that adds +25% health, because that would "waste" 24% of the pickup
- **Player progression:** long term economy like experience points, perks, upgrades, gear
    - example: the player has 99% health, but they have an upgrade that gives +100% damage if they are at full health, so they decide to pickup a +25% health item anyway because the damage bonus is worth more than the wasted healing

> "We tried to model our expectations for gear acquisition and progression in a way we felt would be healthy on paper, and then we constantly playtested and iterated on things to try to get the reality of the playtest to match our models. 
>
> [Here's a spreadsheet with] planned power level progression, of different gear slots at different points in the game. Each row is a different level in the game chronologically. Each column is a different piece of gear, and these are the levels that we expected you to get that gear to at that point in the game. We would constantly cross reference what we thought should be happening with what was actually happening in playtests...
>
>One trick we used is to [make upgrading existing gear more expensive than buying new gear] so you had a temporary incentive to find new gear [...] Or similarly, reward level 5 armor during exploration content when we knew the resources to upgrade from 4 to 5 weren't available yet, so we were guaranteeing that armor would be exciting and enticing for a short time."
>
>-- Rob Meyer, "Reckoning With Gate: Combat At the Scale of Ragnarok" (2023) (YouTube)

## Combat examples
Here we summarize three major approaches to combat:
- **Classic combat** (Doom, Quake) focuses on **movement**
    - **Soulslikes** (Dark Souls, Bloodborne, Elden Ring) require **dodging**
    - Fights are usually close range and continuous.
- **Military realism** (Counter-Strike, Call of Duty) is about **aiming**
    - **Battle royale** (Fortnite, PUBG, Apex Legends) adds more **economy**
    - Fights are often long range and erratic.
- **Modern combat** (Halo, Team Fortress 2, Overwatch) emphasizes **damage**
    - **Cover shooters** (Gears of War, Uncharted) add **positioning**
    - Fights are usually mid range and rhythmic.

Note: no game fits neatly into a category. These are just examples / just one way to think about these games.

### Classic combat
Combat in Doom (1993) features a strong built-in auto-aim assist. The player cannot even look up or down vertically. Doom is clearly not about aiming. Instead, Doom's high speeds enable levels with large enemy counts, encounter variation, and huge sprawling level layouts.

> "[The player] runs at about 50 scale miles per hour – nonsensically fast by modern standards. Most of Doom’s enemies don’t have instant-hit projectile attacks, and most of the ones that do are quite weak – the lowly trooper and sergeant. Every other enemy projectile takes time to reach its target, and would look comical in a more realistic visual presentation.
>
> So because the player moves so quickly in Doom, and because most enemy attacks are dodgeable, the player can avoid a significant amount of damage simply by moving. [...] This frees up Doom’s encounters to feature huge numbers of enemies, to vary scenarios by mixing in different proportions of threats, and to have huge, sprawling, often non-linear spaces that the player can traverse easily." 
>
> --JP LeBreton, Coelacanth: Lessons from Doom

Dark Souls-like action RPG games formalize dodging mechanics via "dodge rolls" with "invincibility frames" (I-frames) providing complete damage negation with good timing. Learning how to read enemy moves, and repositioning / dodging to avoid damage, is often more important than using the best weapon or having the best equipment.

### Military realism
The original Counter-Strike (1999) popularized competitive team-based multiplayer in a realistic military style. Weapons are highly lethal and fights end within a few seconds. Success depends on fast reaction speed and aiming in the right place at the right time, while clearing firing angles and sightlines -- but flashbangs and smoke grenades can deny visibility. Varied gun accuracy, recoil, and bullet penetration mechanics supplement this focus on looking and aiming.

The more recent battle royale genre began as a mod for a realistic military sim shooter series called ARMA, and much of its approach carried over to PUBG: Battlegrounds, the first commercially successful battle royale shooter. This persists even in less militaristic battle royales like Fortnite or Apex, where it is still very common for new players to die suddenly to an unseen sniper a hundred meters away. However, this all depends on a player's ability to accumulate supplies and guns, adding an inventory management aspect and RPG-like progression to each round.

### Modern combat
In Halo: Combat Evolved (2001), the player moves slowly with a very floaty jump, so there's not much dodging here. But there also isn't much aiming either; the default pistol is notoriously one of the best weapons in the game, allowing cheap frequent mid-range / long range headshots with a subtle auto-aim "magnetism" well-suited for casual console play. Instead of movement or aiming, Halo is about managing damage:

>"In almost every modern FPS, the player moves fairly slowly and a huge proportion of enemies are equipped with instant hit attacks – pistols, machine guns, sniper rifles. This usually puts the player in the role of “damage sponge” – they’re intended to soak up a certain amount of damage from mostly unavoidable enemy attacks, then seek cover and heal up. Halo’s recharging shield makes this mechanic quite explicit – by default, you’re exposed to damage and will die, while seeking cover halts that and completes the basic cycle of any combat."
>
>-- JP LeBreton, Coelacanth: Lessons From Doom

Multiplayer team shooters like Team Fortress 2 strongly emphasize healing, to the extent that every team always needs a healer. Overwatch builds on Halo's regenerating shield mechanic. Cover shooters like Gears of War or Uncharted feature regenerating health, but tie this rhythm to hiding behind objects. Modern combat is about getting shot at, alternating periods of risk and rest.

## How to build combat
- blockout a test arena
    - open area and/or 3 lane
- place some enemies
- playtest and repeat
- how to know when combat is "good enough"?

## Key concepts for combat levels
Once you've established the core combat systems, either by playing the game you're modding or by building your own combat from scratch, then you are ready to start designing more specific combat scenarios:
- **Enemy design is about defining different hostile NPC types.**
    - Ideally, each type has distinct behaviors, strengths, and weaknesses.
    - Without a roster of varied enemies, fights will feel repetitive.
- **Encounters are structured battles against NPCs.**
    - Open-ended combat puzzles; player must usually improvise a solution
    - Implementation usually involves some scripting.
- **Cover is about building spaces to fight from.**
    - Where is safe, and where is high risk? Where can players fight or recover?
    - Cover varies with mechanics / weapons. You need core combat design first.
- **Map balance is the fairness of the player's options, usually in PvP.**
    - Where can the player go, what territory can they control? How will the player know?
    - A balanced level helps players trust the layout and invest in the outcome.

We recommend approaching combat in the order listed above. Each aspect depends on the previous one. To build encounters, you need enemy design first. To coordinate cover, you need an idea of how the encounter should play out. To balance a map, you need to know which cover patterns make sense.

## To review...
- **Combat design** is about designing systems for physical conflict.
- To make combat levels, you first need a combat game. But making an entire game is hard, and this is just a level design book. Modding a game is easier.
- Common combat systems include:
    - **Combat mechanics** like aiming, dodging, timing, etc.
    - **Weapon design,** a varied set of interesting tools to use
    - **Economy,** systems of costs / benefits for weapons, inventory, and progression
- Some combat examples:
    - **Classic combat & soulslikes** emphasizes speed and dodging fire
    - **Military realism & battle royales** make guns and aiming more important
    - **Modern combat & cover shooters** are about managing health / damage

## Further reading on combat design
- ["Reckoning With Fate: Combat At The Scale of Ragnarok" (2023) (via YouTube)](https://www.youtube.com/watch?v=6iTBqcBv5QA) is the most comprehensive talk on modern AAA combat design from Rob Meyer, lead combat designer on God of War: Ragnarok (2022). Meyer gives specific examples from his work and details the responsibilities of a combat designer at Sony Santa Monica.