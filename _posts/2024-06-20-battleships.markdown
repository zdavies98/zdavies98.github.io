---
layout: posts
title:  "Battleships"
date:   2024-06-20 04:11:16 -0000
tags: [tutorial, javascript]
author_profile: true
author: Zachary Davies
categories: work
tagline: "How to build Battleship: The Game in Javascript"
header:
  overlay_image: https://images.unsplash.com/photo-1661015951889-3cab32166ff8?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
  teaser: https://images.unsplash.com/photo-1661015951889-3cab32166ff8?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
  
  caption: "Photo credit: [**Unsplash: William Rudolph**](https://unsplash.com/@william_rudolph)"
description: This article shows how to code the classic Battleship game.
---

> To see a preview of this project go to [Battleships on Codespaces](https://scaling-space-fortnight-wxvxjvqvv9xh96xj.github.dev) and select the `index.html` file and then `Go Live` on the status bar.

## Background
As a software engineer that works primarily in Javascript, I wanted to see what other fun projects I could work on. I figured, why not try to develop one of my favorite childhood games: Battleship!

## Approach
I wanted to make this a simple project that would be easy to manipulate in the future. I broke down each step and coded each piece of functionality I wanted my game to have.

## Results
In this game, the user is able to place all their pieces, and start the game. After the user plays their first turn, the computer then takes it's turn. Turns alternate until one side sinks all the other's ships.

## Next Steps
There are a few improvements I want to make with this game. First being design, I would like to upgrade the styling to be more similar to the original game. Next, I want to add some logic to the computer's turn, since every guess is random. Rather, I would like the computer to have some basic logic to select spaces near a hit, as a human would. The end goal is to eventually make this game multiplayer.