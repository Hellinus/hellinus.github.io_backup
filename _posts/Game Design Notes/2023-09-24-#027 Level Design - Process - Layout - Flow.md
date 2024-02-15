---
title: "#027 Level Design - Process - Layout - Flow"
date: 2023-09-24 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Level]
---

> How it feels to move through the level.<br>
> From [The Level Design Book](https://book.leveldesignbook.com/).

In level design, **flow** is how it generally feels to move along different paths / between different parts of a level. 

Is the path simple or complicated? Straight or curvy? Slow or fast? All of these factors affect the player's movement through the space. In short, designing flow is about **designing movement.**

You should start designing flow during initial layout planning, but you won't be able to verify how it actually feels until you blockout and playtest.

> Do not confuse flow (level design) with flow (game design), the theory that players enter a highly-engaged "flow state" when skill and challenge are in equilibrium.

## How to feel the flow
Level design is kind of like motor racing. What type of movements do we ask the player to make? Does it feel safe or dangerous, simple or complex?

On the multiplayer map de_dust2 by Dave Johnston, iconic "Dust doors" (below) funnel players into a narrow dangerous zig-zag turn. An opponent on the other side can even shoot through the thin wooden doors. Like the Eau Rouge, you never know 100% what's on the other side. This is more exciting than a straight clear open path.

## The best flow?
"Dust doors" could be considered "bad" flow -- the doors break the line of movement and force sharp sudden careful turns. But here, the so-called bad flow is actually good, it adds drama and strategy within the context of Counter-Strike's fast paced fights.

Sometimes fast is good, sometimes slow and complex is better. It all depends on the game systems and the level's purpose.

Fast-paced arcade-style games might favor smooth flow with wide generous turns and minimal interruptions. Meanwhile a horror walking simulator might work better with sharp narrow turns, blind intersections, S-shaped curves, and maze-like dead ends. 

In the end, **the best flow is whatever supports the intended experience design goals.**
- What is this level / area / encounter / experience about? Fast exciting action, calm observation and navigation? The first glimpse of a big city? A scary chase? A hangout?
- For competitive multiplayer maps, flow strongly affects overall map balance.
- To verify the flow works as intended, you must blockout and playtest.

## Verticality
**Verticality** is vertical flow, how it feels to move upwards and downwards.

In a map, this usually means stairs, ramps, slopes, elevators, ladders, cliffs, raised platforms, jump pads, etc.

The conventional wisdom here is that more verticality is better, since it adds more visual interest to the map structure and breaks up a floor plane. But today, we advise against too much random verticality, and instead urge restraint. The suitability of verticality depends a lot on the core game design; many game mechanics require spaces that are just big flat floors, and sometimes that's ok. You don't need to put random steps and platforms everywhere.

## How to design flow
Flow is about **designing movement.** A lot of factors affect how movement feels:
- **Speed.** Does it feel slow or fast to move along a path?
- **Direction.** Is the path smooth / continuous, or disjointed / abrupt with sharp turns?
- **Wayfinding.** Is the path obvious? What info helps the player plan a route?
- **Metrics.** What are the player's movement mechanics? How are distances tuned?

To consider these factors all at once, we offer three design techniques for designing flow:
- **Desire lines:** compare ideal paths in a single room / area
- **Critical path:** visualize single player pacing across the whole level
- **Circulation:** visualize multiplayer lanes across the entire map

### Desire lines
In urban planning, **desire lines** (or **desire paths**) are user-made paths marked by foot traffic and erosion.

In the photo below, an "unofficial" dirt path deviates from the "official" concrete path. The unofficial path is the desire path. It is what player actually want / and what feels most natural and intuitive to them.

> Sometimes IRL architects pave desire paths into official paths. In level design we respond similarly, by observing playtests and adjusting accordingly.

This type of thinking is useful for designing small scale flow, within a single room / area:
1. Imagine an efficient "desire line" from the player to their destination.
2. Compare the desire line against the actual path(s) the player can take.

In the example diagram below, a player must climb stairs to reach an exit...

The player's desire line (yellow) leads directly to the exit on the second floor, but the actual flow (red) forces the player onto the stairs. 

The switchback stairs (left) feel less straightforward than the single turn corner stairs (right), because the switchback requires the player to make an extra turn.

While the switchback is less efficient, remember that **less efficient flow is not necessarily bad.** The switchback could be useful:
- Slow down the player, and encourage room exploration first
- Offer a parkour-style shortcut, climb directly up to the mid landing
- Place a ranged enemy on the mid landing; how easily can the player attack it?

### Critical path
The **critical path** (or "golden path") is the minimum / main path to complete a single player level.

More generally, it represents an idealized player flow that highlights the most important ("critical") parts of the level and mandatory game content that you want every player to experience.

Single player layout drawings usually need some sort of labeled critical path. Sketch, highlight, or mark the critical path in the drawing -- or if the drawing is too complicated, at least mark the player start, exits, and labeled points of interest.

### Circulation
**Circulation** (or "connectivity") refers to how areas connect to each other.

Designing with circulation can help support a level's storytelling and wayfinding. A level with plausible circulation might resemble the way that real world architecture functions, thus allowing players to read and predict patterns based on their general knowledge from outside of the game.

Circulation analysis is especially helpful for multiplayer map design, which is often more non-linear and does not follow a single critical path. Instead, we organize the level layout into a system of lanes.

## To review...
**Flow** is about how players move around a level. Verticality is vertical flow.

When **designing movement,** think about speed, direction, wayfinding, and metrics. Yeah, it's a lot.

Three ways to think about flow:
- **Desire line:** compare ideal path vs. actual pathing within a room / area
- **Critical path:** the ideal player path to complete a single player level
- **Circulation:** connective areas / "lanes" of the level

**Flow is a tool.** Inefficient "bad" flow is not necessarily bad, because it can serve a purpose in the right context. Similarly, overly efficient "good" flow can feel boring. It all depends on your design goals.
