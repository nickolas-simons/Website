---
layout: post
title:  "Othello Game"
summary: "Haskell,GitHub,No-Engine"
preview: /assets/othello/othello_preview.webp
image: /assets/othello/othello_preview.webp
background: "/assets/site/background.avif"
location: "UNDERGRAD"
order: 6
---

![Title Image](/assets/othello/Othello_Title.webp)

### Overview
A final project developed for CS340: Programming Patterns and Paradigms, this is an ASCII-based Othello game created in Haskell. It features a computer-controlled opponent and supports variable board sizes.

{% include github-button.html url="https://github.com/nickolas-simons/Othello" %}

### Development Details  
**Tools:** Haskell stack

**Time:** April 2022

### Key Features

##### Haskell Development

Modelled and implemented the game Otherllo using Haskell, applying functional programming concepts and utilizing game state tree search for game AI.

##### AI Opponent

Implemented a computer-controlled opponent using mini-max algorithm on a pruned game tree, allowing for strategic AI gameplay. (i can't beat it anyway so that must mean something)

<div class="video-max-wrapper" style="width: 100%; max-width: 800; margin: 0 auto; aspect-ratio: 16 / 9;">
  <video 
    controls 
    style="width: 100%; height: 100%; display: block; object-fit: contain;">
    <source src="/assets/othello/OthelloDemo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
