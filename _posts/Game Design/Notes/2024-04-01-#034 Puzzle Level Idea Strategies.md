---
title: "#034 Puzzle Level Idea Strategies"
date: 2024-04-01 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Mechanics, Puzzle]
---

From: [Puzzle Level Idea Strategies by Patrick Traynor](https://cwpat.me/misc/puzzle-level-idea-strategies/)

## Strategies
### Find an interaction and force it
Build a puzzle around a specific interaction or move being required to solve the puzzle. 

### Mingle mechanics
Pretend all mechanics are invited to a party. 
- What happens when mechanic A meets mechanic B?
- What conversations would they have?
- Would mechanic C be interested in this conversation too?

### Enumerate all mechanic pairs
List all mechanic pairs (for some definition of "mechanic" that's useful for this exercise) and brainstorm about each individual pair.

### Enumerate action sequences
List out actions your game has (for some definition of "action" that's useful for this exercise), then list out many sequences of these actions, and try to make levels with those sequences as the solution.

> If your actions are A, B, and C, try making a level which forces you to do A then B, another level for B then A, another for AAB, ABA, ABB, etc.

### Try extremes
Extreme layouts can be interesting, and can sometimes have an entirely new set of deductions and theorems.

> Almost all spaces are crates, almost all spaces are players, etc.

### Try interesting geometry
Try interesting geometry, such as a level only 2 cells wide, a symmetric level, a really big level, a level with no walls, etc.

### Mess around in a big playground
Make a big playground level, with lots of objects and structures, and mess around and see what you can do in it.

### Randomly place objects / doodle in the level editor
Doodling random, chaotic, abnormal, and silly structures in the level editor can spark ideas you wouldn't have thought of otherwise. This is more useful than it might sound!

### Create an impossible level, then make it possible
Create a level that is obviously impossible to solve. Then, using that as a starting point, keep making adjustments to make it possible, and see where you end up. Or, come up with a loophole to solve a paradoxical situation, and then camoflage the loophole.

### Create an impossible level, then try to solve it anyway
Create a level that is obviously impossible to solve. Now, try to solve it anyway.

### Create a possible level, then make it impossible
Start with a level that's possible to solve, and keep making changes until it's impossible, then undo your last change.

### Teach something you want the player to learn
Find something you want the player to learn, such as a specific rule, edge case, or technique, and make a level that teaches it.

### Find an interesting deduction and force it
Find an interesting deduction you can make in a specific setup, and try to build a puzzle around that deduction being the lynchpin.

### Make a forward design chain
Follow the "forward design" approach: start from a blank slate, and place objects to create a sequence of deductions, such that the player also follows that exact same sequence of deductions.

### Make a setup with an invariant
Build a setup with some invariant, such as a geometrical invariant, a topological invariant, a sequencing invariant, and build a puzzle around that.

### Induce emergent phenomena and patterns
See if you can induce or find emergent phenomena or patterns, such as parity, loops, reversibility of actions, equivalence of actions, etc.

### Implement gadgets
See if you can implement gadgets and mechanisms using the game's objects, such as a one-way tunnel, a one-use tunnel, a 15-puzzle, a binary counter, a combination lock, etc.

### Implement puzzle tropes
See if you can implement other common puzzle tropes from puzzle games, such as two tasks that are in conflict, re-opening a door to bring an early object to a later area, etc.

### Start from a theme
A geometrical or narrative "theme" can be a good premise for a level.
> A level about using a lot of 2x1 blocks, a level about escorting an object through many obstacles, a level where 2 characters help each other out, etc.

Also, depending on the game, you can try making a puzzle with a constraint, layout, or solution that's relevant to the setting or the narrative.

### Aim for a feeling
Make a level where the player feels strong, claustrophobic, surprised, etc.

### Tell a joke
Take a mechanic to its logical extreme, find a comical setup, build a Rube Goldberg machine, build something absurd, use objects in unusual or silly ways (e.g. a useful object is now a hindrance, or vice-versa), make a puzzle that looks hard but is actually easy, etc.

### Keep your eyes open for "things almost happen" moments
Sometimes, a playtester has a plan or theory to solve a puzzle that doesn't quite work out for whatever reason. And as a developer, you may come up with these failed theories when making puzzles, or when watching people play. "That could have been a solution!" Try to make a different puzzle where that thing that almost happened, actually happens!

### Clarify a misunderstanding or reinforce a theorem
Paying attention to initial playtester misunderstandings of rules can give an idea for a puzzle to further clarify a rule, or spark a new idea. Similarly, try making a puzzle to reinforce understanding of a theorem that a playtester might not fully grasp, or explore further applications of a theorem.

### Turn alternate solutions into separate levels
When you or a playtester finds an alternate solution to a puzzle, you may end up editing the puzzle to disallow it, but also consider making a second puzzle where that alternate solution is actually forced!

### Jump off of other games' levels
Look at the Microban puzzle set, the original Sokoban, or another applicable game and check if those levels are solvable in your game's ruleset, possibly slightly altered, and see where you end up.

### Translate puzzles
Choose a game that is wildly different, and try to translate one of its puzzles into your game.

> Translate a puzzle from Portal into your grid-based sokoban game. The process of trying to fit that square peg into the round hole is difficult and messy, and you can end up with something new and unrecognizable.

### Bisect two levels
Take two puzzles you already have, and design the puzzle that would be "between" those two. E.g. a puzzle inbetween a super simple and super complicated puzzle, or a puzzle that shares ideas between both.

### Back-design a hard puzzle into an easy one
Using an easy puzzle as a starting point, make a hard puzzle and solution using the same level geometry. This is especially applicable for games with meta-puzzles or multiple level goals.

### Use computer generation or solvers
Some people use programs to randomly generate levels according to heuristics, and then revise the levels from there. And some people use puzzle solver programs to aid in the process of mutating and refining levels. Personally, I'm not familiar with either, and I haven't found any resources to easily try either technique myself, but I'm listing them here to be thorough.

## Other notes
### Trial and error is part of the process
In my experience, many puzzle ideas do not materialize into an actual puzzle, or they materialize into a not-so-great puzzle. Personally, I've gotten used to doing lots of digging, and having lots of unused puzzle drafts without feeling dejected about it. But also, on the flip side, sometimes an idea can lead to multiple puzzles instead of just one! You never know.

### Investigate variations while iterating
While iterating on a puzzle, either during initial construction or when refining it, be open to potential variations on it which could be their own puzzle, such as a related idea, a slightly different setup, a different mechanism to enforce the same constraint, a harder version, an easier version, a twist to put on the puzzle, etc.