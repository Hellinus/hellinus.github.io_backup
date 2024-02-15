---
title: "#022 Level Design - Process - Pre-production - Worldbuilding"
date: 2023-09-18 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Level]
---

> How to conceptualize and design the fictional history of the game world.<br>
> From [The Level Design Book](https://book.leveldesignbook.com/).

## What is worldbuilding?
**Worldbuilding** is the high level conceptual process of designing the setting and history of the fictional game world. 

We inherit this process from fiction writing, especially from science fiction and fantasy (SFF) writers who often construct "bibles" that detail backstory, lore, and characters' relationships in exhausting encyclopedic detail. 

Your worldbuilding docs could describe the planet's climate, detailed political histories that predate in-game events, or even mundane details like when does everyone get up in the morning, or what the protagonist's mother enjoys for dinner.

## Worldbuilding for games
### Avoid premature worldbuilding
Because this is a level design book and not a narrative design book, we take a predictable stance here: ***avoid premature worldbuilding.*** Worldbuilding is work, and if you do too much worldbuilding too early, then it is also unproductive unnecessary wasted work. At first, **worldbuild only what you need.**

Throughout pre-production, the shape and content of your game world might change drastically. If you start worldbuilding small details too early, then it'll likely be wasted work. What if you write 10 pages about the history of a house, only for the house level to be cut from the project? What if you write 20 pages about some monsters and their culture, only for you or your team to scope down later and replace the monsters with recycled human NPCs? Avoiding detail helps you stay flexible and less frustrated with the project.

While worldbuilding can be fun and useful, for novices it more often distracts from the basic core work of telling a compelling story with characters and actions. Remember that your favorite epic fantasy, sci-fi, and superhero worlds have been constructed over decades (or centuries) by thousands of experienced professionals with substantial funding over countless iterations. When working alone, worldbuilding yourself into a hole is a great way to avoid making a game.

### Embrace functional worldbuilding
[Clint Hocking coined ludonarrative dissonance](https://clicknothing.typepad.com/click_nothing/2007/10/ludonarrative-d.html) to describe situations when the player's performance ("ludo") and the designer's intended story ("narrative") don't work together ("dissonance").

However, the vast majority of players tend to tolerate a great deal of dissonance in their game worlds. Fan wiki commentators will debate lore consistency, and game critics will point out embarrassing incoherence, but the average player will shrug and move on. Shooter games feature walls that are utterly impervious to nuclear explosives and world-ending magic energy. Every RPG routinely revives dead characters during the game, but arbitrarily kills off characters permanently, with no elaboration on the metaphysics of permadeath. Every action hero is a sociopath who murders thousands of people with no remorse. None of this incoherence feels particularly dissonant to its audience.

So in this book we embrace a **functionalist** attitude toward game narrative: fictional storyworlds in video games serve a crucial design function to smooth over the inherent incoherence of interactive systems. That is, **story solves game problems.**
- Design problems: is the player "moving through repetitive corridors and shooting squares", or is the player "escaping an alien invasion of a vast underground military complex"? 
- Technical problems: is the monster "unable to navigate water due to broken pathfinding AI", or is the monster "afraid of water"?

## Minimal worldbuilding
For most level design projects, we recommend starting with a minimal psychological approach: **worldbuild the bare minimum necessary** to establish the level setting and support experience goals. 

To plan a basic level, you only need to worldbuild enough to answer three basic questions:
1. **(Past) Who made this place?** (Why? How will the player know?)
2. **(Present) Who lives here now?** (Why? How will the player know?)
3. **(Future) How can the player affect this place?** (Why? How will the player know what happened? How will the inhabitants react?)

These answers can be simple. Here's an example for an action game level with minimal story: 
1. Who made this place? **A human family built a log cabin.**
    (How will the player know?... It'll look like a log cabin, built at human scale, with human furniture and multiple beds inside.)
2. Who lives here now? **Some monsters ate the humans.**
    (How will the player know?... There are monsters and old bones inside, and no living humans.)
3. How can the player affect this place? **The player can kill the monsters.**
    (How will the player know?...  The monsters are hostile and will attack the player on-sight.)

Even this short premise already has so much potential for future storytelling. What type of log cabin is it, how big was the family, why did they settle in this exact spot? Why did monsters attack the humans? What if there was an alternate way to resolve this encounter, without killing the monsters? How can the theme of "family vs monster" resonate throughout the rest of the level, or the rest of the game?

## Comprehensive worldbuilding
For large long term projects (more than a few levels / few months) then it makes sense to commit more fully to the game world and its fiction. Worldbuilding bibles are generally made of three types of worldbuilding design documents: maps, timelines, and notes. 

*To organize worldbuilding documentation, use a personal wiki or note database -- see Tools.*

### Maps
Draw a map of the fictional game world, beyond the playable area in the game. What is the level's relation to the larger world or universe? Mapmaking is a very common worldbuilding trope in fantasy genre novels. And for level designers, a map is probably the most immediately useful worldbuilding tool.

The simplest way to engage the player is with plausibility. If you're new to worldbuilding, you should start with something familiar and Earth-like for now.

#### Terrain / climate map
First, draw a large scale map focused on terrain and climate. To design something plausibly Earth-like, start with some basic earth science principles: 
1. Draw **continents.** Simulate continental drift and make sure they fit together like puzzle pieces.
2. Draw **wind** systems and **latitude.** Prevailing winds change with latitude and interact with landmass.
3. Draw **mountains** and **lakes.** Mountains form along fault lines or volcanos. Rivers generally flow from atop mountains or lakes and downward toward the ocean.
4. Label **climates.** It's hotter toward the equator, colder toward the poles. Mountains can block or trap rainfall. Is it humid, windy, rainy, stormy?

*For more on researching and designing terrain / biomes, see Landscape.*

Once you have a solid base world, you can make it feel more unique or fantastical by selectively exaggerating certain aspects.

In the example map above, author N.K. Jemisin made a world with two continents slightly above the equator. Then Jemisin focused on a section of high energy equatorial ocean between the two continents, and amplified it into a "hell corridor" called the "Sea of Tears" where valuable "Furywood" trees grow along its coast. While an area plagued by constant tsunamis that temper magical trees is implausible by itself, it feels much more plausible and special when integrated within a more mundane world.

#### Political maps
With an established natural world, you can now begin populating it with people. Where do they live and why? What is important to them?

When designing societies, author N. K. Jemisin strongly recommends some basic sociology and doing research -- and avoid relying on thinly veiled stereotypes of existing real world cultures.

Needless to say, mapping societies and territories is extremely complicated in the real world. People go to war over borders, region names, and political identities all the time. This conflict and tension is probably what makes your world interesting, so embrace mapmaking as the messy political design process that it is.
- **Define the mapmaker,** who are they and what are their motivations? What is their relationship to the area that they are mapping?
- **Sketch multiple maps of the same area,** but from different perspectives. What did the area look like 100 years ago, or 500 years ago? Would different characters with different backgrounds draw the same place differently or use different names? Where is the ambiguity and conflict in your world? A "wrong map" might be more interesting than an accurate map.
- **Draw non-geographic maps,** without borders or landmass. What would a "social map" of a city look like? What about an economic map, or an emotional map?
- **Leave some areas blank,** because not every part of the world is immediately relevant or knowable to everyone. No adventure or exploration is possible without mystery.

### Timelines
Plot a history of the game world, across days, months, years, or even centuries, accompanied by short  annotations and labels. 

What is the history of this area or place? How have the people changed? Just as with geography, history is also a deeply political craft that changes based on whoever is doing it. When writing a history you must consider the historian and their background, who their audience was, and most importantly, what they exaggerate and what they omit from their account.

Again, the goal is not an authoritative factual history that definitively answers every question. Think about the big idea or theme that each history evokes.

(example timelines from Heaven's Vault?)

- **Define the historian,** where and when are they writing from? How would their perception, memory, or access be shaped by their time and place?
- **Design multiple timelines that overlap,** ideally with specific similarities and contradictions.
- **Leave forgotten holes in each timeline,** think about what the historian forgot or what they misremembered. Part of your in-game experience could involve rewriting history, filling in these gaps, or identifying new holes in history that no one knew was there.

### Notes
While level designers may prefer visual documentation, narrative designers and writers tend to rely primarily on written **notes,** often stored on index cards, private wiki, or some other organizational system. These notes might include:
- Character biographies, daily routines, family history
- Location descriptions, travel guides, geological or ecological surveys
- Cultural primers, religious scriptures, local histories
- In-world books, pamphlets, speeches

### Do some dove shit
One widely shared piece of worldbuilding advice from now-deleted tumblr user kuusamaagi:
> ... You can, and actually should have weird and impractical cultural things. They’re not inherently unrealistic, for as long as you address the realistic consequences as well.
>
> Let’s say you’ve got a city where there’s tame white doves everywhere. They’re not pests, they’re regarded as sacred, holy protectors of the city, and the whole city cares for them and feeds them like they’re pets. They’re so tame because it’s a social taboo to hurt or scare one. Nice pretty doves :)
>
> Then someone points out that even if they’re not seen as pests, doesn’t having a completely unchecked feral pigeon population - that not only isn’t being culled, but actively fed and cared for - mean that there would be bird shit absolutely all over the place?
>
> A part of you wants to say no, because these are your nice, pretty doves. To explain that there’s a reason why they’re not shitting all over the place, maybe they’re super-intelligent and specifically bred and trained to not shit all over the place. The logistics of how, exactly, could anyone breed and train a flock of feral birds go unaddressed.
>
> An even worse solution would be to not have those birds, editing them out of the world. No, they spark joy, you can’t just toss them out!
>
> Now, consider: Yes, yes they would, but the city also has an extensive public sanitation service that’s occupied 90% of the time by cleaning bird shit off of everything. One of the most common last names in the area actually translates to “one who scrapes off dove shit”, and it’s a highly respected occupation. And thanks to the sheer necessity of constantly regularly cleaning everything, the city enjoys a much higher standard of cleanliness, and less public health issues caused by poor public sanitation.
>
> The doves do protect the city. By shitting fucking everywhere.
>
> -- kuusamaagi (via now-broken tumblr link)

## Examples of worldbuilding
### The Witness (2016)
If you have a lot of time and money, doing full ecological, historical, and architectural development of your game world can be rewarding. Thekla Studios spent $6 million USD across seven (7) years to build the first person puzzle exploration game The Witness, and hired landscape architecture design firm Fletcher Studio to build up the architectural history and logic for its main island.

Fletcher proceeded to redesign the island incorporating different ecologies, climates, geologies, and architectural styles for the game world, while reconciling this worldbuilding with the already existing blockout and puzzle design.

> "We first set out to reverse engineer the Island, as it might have existed before civilization. Hundreds of Islands were identified and studied, in the search for small, temperate islands that have a rich history of isolated civilizations. Known as Europe’s secret Islands, the Archipelago of the Azores offered the most material to work with. The layers of different cultures, from ancient civilizations to the Portuguese monarchy, to present day fishing villages, proved most analogous. Available aerial imagery was collected from the Azores and then collaged together to create a fictional Island in plan, now with topography, beaches, water bodies, etc..."
>
> "We also wrote an environmental narrative for the Island, which formed the basis for design in subsequent phases. Through determination of solar orientation and dominant winds, the studio was able to establish the crucial gradients of wet and dry, windward and leeward. We then diagrammed the underlying geology, establishing assumptions regarding rock types, soils and substrates. The resultant mash-up of granite, basalt cinder cones, limestone and loose sandstones were located in specific zones and guided building materiality, soil types, and subsequent biomes. Using these fundamental climate and geological assumptions, we began to develop a set of simple ecological rules that established the make-up of the Island’s ecologies, and their bordering ecotones.
>
>... The past was divided into three successive epochs, which we termed Civilizations (CIV’s) One, Two and Three. A simple description of each was developed, and then a larger matrix, was produced that related to each in terms of infrastructure, architecture, and landscape. Each of these three categories had their technologies, agriculture, religion, and cultures. Materially, each epoch had its own techniques of building, based on assigned resources and technologies, with each CIV methodologies and products growing more refined over time..."
>
> "... In our narrative, the Windmill began as a CIV One sacred mound, whose rock was reused to construct the foundation for a watchtower in CIV Two. Civilization Three then adapted the tower, as a means to pump freshwater from the reservoir to the rest of the island.
>
> Often, once a structure had been given meaning, it then inspired the addition of other landscapes and infrastructures. The existence of the Windmill necessitated the addition of a lake, a small stream, and eventually a dam and a logging flume. There was a growing reciprocity between the gameplay, architecture and landscape with the island environment and story. 
>
> For example, the use of a given building material, lead to the creation of a logged forest, a rock quarry, a glass factory. Puzzles were added to support the resource extraction and manufacturing narrative: A shipping freighter was added to justify the use of steel on the island. This ship was perhaps the source of something that not be easily made on the island, and much of it’s iron had been harvested, and can be seen in various states of reuse throughout."
>
> -- from "The Witness: Designing Video Game Environments" by Fletcher Studio, 26 May 2017

## To review...
- **Worldbuilding** is about designing the history and conceptual setting of the entire game world.
    - Worldbuilding in games is either developer-facing (**documentation**) or player-facing (**lore**).
    - For level design for action games, **don't do too much worldbuilding too early.** It's much easier to change worldbuilding to accommodate a level, rather than the other way around.
- **Minimal** worldbuilding: who built this place, who lives here now, and what can the player do here? For most levels, simple implied answers are enough.
- **Comprehensive** worldbuilding: design maps, timelines, and notes. Again, only do this if your project is big or if you're working in a team.

## Further reading / sources
[Story as a function of gameplay in First Person Shooters and an analysis of FPS diegetic content 1998-2007](https://researchportal.port.ac.uk/en/studentTheses/story-as-a-function-of-gameplay-in-first-person-shooters-and-an-a)

["Worldbuilding 101: Growing Your Iceberg"](https://nkjemisin.com/2015/08/worldbuilding-101/)

[Virtual Cities: An Atlas & Exploration of Video Game Cities](https://www.game-cities.com/virtual-cities)