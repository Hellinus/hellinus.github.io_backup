---
title: "#028 Level Design - Process - Layout - Flow - Circulation"
date: 2023-09-25 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Level]
---

> How areas link to other areas, the "connectivity" of a map.<br>
> From [The Level Design Book](https://book.leveldesignbook.com/).

In architecture, **circulation** generally refers to the "in-between" areas that connect other areas, like hallways, aisles, and stairs.

Some level designers call this connectivity. But for this book, we think circulation is a better word and concept that more level designers should adopt.

## Types of circulation
Real world architects distinguish between several types of circulation:
- **Primary** vs. **Secondary** circulation (path to main elevator vs. path to storage closet)
- **Public** vs. **Private** circulation (ground floor lobby vs. bedroom hallway)
- **Horizontal** vs. **Vertical** circulation (hallway vs. stairs)

Many of these concerns often don't directly apply to level design. Unlike sad unfortunate real world architects, we can design virtual buildings without any concern for building codes, ordinances, or thermodynamics. However, these words and concepts are still useful.

In level design, there are at least two more different types of circulation:
- **Diegetic circulation:** look and feel of the circulation, the in-game fiction of the space.
    - intersects with environment art and storytelling
    - crucial for single player levels, especially in a realistic style
- **Formal circulation:** systemic function of the circulation, despite any in-game fiction.
    - more about the combat design, cover patterns, and map balance
    - important for multiplayer maps, especially competitive combat

## Diegetic circulation
**Diegetic circulation** refers to how fictional in-game characters would use the space. 

In film studies, diegesis is the imaginary fictional world depicted on screen. Ask yourself, how would players roleplay their movement through the level? What is the theme of this space? What is the story behind this circulation pattern?

For single player levels, conveying circulation is crucial for narrative. If you want your level to feel like a plausible real-world space, then you must also think like a plausible real-world architect with plausible real-world circulation.

When designing their exploration game Gone Home (2013), The Fullbright Company chose to work with an old mansion theme because modern suburban houses orbit around a central room with flat dense connectivity, but mansions branch deeply into distinct wings. This mansion trope supported the hub-and-spoke typology they wanted, which helped them tell the story they wanted.

The first half of Gone Home's critical path starts from the "Front Porch" (bottom center) and ends in the Basement (top left) while frequently backtracking on itself, resulting in a free-form exploration feel that supports Gone Home's experience goal of investigating an empty mansion.

It wouldn't feel like an investigation (nor a mansion) if every clue led to a new area. Instead, we learn to dwell in this space and grow more familiar with it. In this way, architectural research is crucial for levels focused on story, otherwise the diegetic circulation may not support the desired critical path.

### Diegetic circulation as wayfinding
Players follow circulation based on their current objectives. If they must find the exit, then players will follow primary circulation. If they need to reach the roof, players will look for vertical circulation. If players need to sneak around or explore for resources, they use secondary circulation.

Generally, wider bigger passages feel like primary public circulation, while narrower areas will feel more like secondary circulation. But imagine walking in a level and seeing a big wide door and a smaller narrower door. Which door leads to the exit? The big door could lead to primary circulation and an exit. But if the bigger door looks like a garage door for a vehicle, then maybe it's locked and we should take the smaller door... so now the smaller door is more likely to feel like primary circulation...

## Formal circulation
**Formal circulation** focuses on the layout's physical function (the "form") and affordance for movement.  

Here we ignore the theme, setting, and culture. Think about the level in terms of abstract level geometric shapes. Ask yourself, how would a professional player or speedrunner understand this map?

### Lanes
**Lanes** are formal primary circulation in a multiplayer map.

Lanes help players predict and coordinate movement. A large map with too many lanes or no clear lane hierarchy will function like a maze; players won't know where to focus their efforts, get lost, and miss each other.

For this reason, most maps use only 1-3 lanes.

### One lane
Payload maps for team-based multiplayer games like Team Fortress 2 and Overwatch focus gameplay and conflict along a single lane that snakes around the entire map. The attacking team must "push" the payload cart forward by standing near it, while the defending team must prevent the cart from reaching the end of the lane. The payload route is prominently marked so that players can easily coordinate efforts (or prepare ambushes). Occasionally, there are extra half-lanes and back alleys to help attackers break through defenses.

### Three lane
Lanes are also common in competitive multiplayer games about territory control such as in MOBAs like League of Legends or military shooters like Call of Duty and Counter-Strike. These games' maps often use a **three lane** format, three bidirectional critical paths that occasionally branch and intersect via smaller lanes. (In MOBAs, the tangle of smaller interstitial lanes / secondary circulation are collectively known as the jungle.)

If an opponent has blocked progress on one lane, then the other player(s) can attempt to flank around them by advancing on another lane. Alternatively, if a player wants to try to avoid conflict entirely, then they can avoid the main lanes and try to farm the jungle.

Lane asymmetry is important, each lane should feel different. In Summoner's Rift (League of Legends), the top and bottom lanes are longer than the middle lane, and the top lane has a powerful boss while the bottom has a weaker mid boss. In de_dust2 (CS:GO), teams must decide whether to focus on site A or B and how to approach or flank; or if the team chooses poorly, they might need to move through the mid lane to the other side of the map.

### Rotating
Rotating (primarily in Counter-Strike) is when players must move from one lane to another. It generally requires teamwork and coordination, and the tension between rotating vs. not-rotating is a core element of team-based competitive multiplayer games.
