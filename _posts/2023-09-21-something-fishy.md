---
layout: post
title:  "Dev Log & Demo: Something Fishy"
summary: "An underwater mystery puzzle"
date:   2023-09-21
preview: /assets/something_fishy/something-fishy-preview.png
---

## The ideation
At the start of the semester, I got back into game development after a whole summer doing software engineering. I found myself asking what if there was a game simulating the experience of being Ariel, full of curiousity for the human world? I ran through a lot iterations for conveying such an idea.\
What if there was a crime taking place by a coast, and you're a fish witnessing it, wanting to piece the truth together?\
What if you're mermaid transformed human thrusted into this murder mystery?\
After some thoughts, I ultimately settled on an idea that I could iterate on faster: the player is a fish stuck in a sunken house, and to find a way out, the fish has to collect clues and keys that unravel the story behind the house. And that's "Something Fishy".

## The process
"Something Fishy" took me longer than expected. There was a lot I had to re-learn and learn like using the shader graph to recreate underwater environment, implementing object pooling to optimize the object inspection system, etc. I'll list all the materials and resources I used to build the game too.

Asides from absorbing all those techniques, I guess a surprising element was how I let gameplay mechanics to naturally emerge out of simplifying the development process. I remembered one time my professor said during a game design lecture: Less is more. When you're stuck trying to make something work, it's mostly better to *subtract* rather than add. I initially wanted to pose a threat and time pressure to the player by introducing a predator roaming around the house, but given the time and resource (aka all by myself), I replaced that idea with a draining water mechanism. As a result, the decision made the game surprisingly more fun for me, as the player not only has to deal with horizontal limitation like locked rooms and chest but also vertical limitation (spoiler: some objects cannot be reached unless the player can replenish the water level). Somehow, one simple subtraction enabled better utilization of a game's space way more than I anticipated.

Here's a sneakpeek 👀 of how chaotic it was to build and learn on the go for this game: 
[🌀 Dev Log](https://www.notion.so/Something-Fishy-Dev-Log-4409445ba00648259e56b910946753a6?pvs=4)

## The first demo
🎥 This is just a snippet of the game
[<img src="/assets/something_fishy/something-fishy-demo.png">](https://clipchamp.com/watch/UMXRn5roG9R)\
[🎮 Download the game here!](https://gumball7112.itch.io/something-fishy)