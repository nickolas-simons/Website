---
layout: post
title:  "Multiplayer Action Game"
summary: "Solo Developer"
preview: /assets/Untitled_preview.png
background: /assets/Untiled_TitleImage.png
order: 4
---

![Title Image](/assets/Untiled_TitleImage.png)

**Overview:**  
A solo personal project designed to deepen familiarity with Epic's Gameplay Ability System, UE5's new animation tools/framework, and the procedural content generation framework. This is intended to eventually be a multiplayer roguelike, but scope is large enough I plan to only focus on multiplayer features for now.

**Platform/Engine:** UE5 for PC

**Time:** Nov 2025 - Present

**Team:** Solo

**EXISTING FEATURES:**
- **PCG Tile Management:**  
   - Implemented a system for randomly generating tile partitions populated using PCG framework
   - Currently only server authoritative, but plan to add client prediction using fixed seeding

![Environment Partition Example](/assets/chunk_loading_graphic.png)

![Environment Partition Example](/assets/Untiled_ReplicationTest.gif)

- **Ability and Attack Tracing System**
   - Developed targeting framework for async traces to interface with GAS targeting system
   - Tracing profile modelled using curves
   - Replication handled using Epic's Gameplay Ability System.
   - Decouples animation from tracing (excluding root motion)
- **GAS Combat**
   - Simple combat featuring elemental damage types and common effects like slow, stun, and poison
   - Replication handled using Epic's Gameplay Ability System
- **Weapon System**
   - Based on Lyra, utilizes ability sets to tie abilities to input actions specified by the item
- **Motion Matching and Mover Component**
   - Based on GASP update, using motion matching and mover component to driven animation
   - Not currently integrated with mouse model

![Hitbox Example](/assets/Untiled_AnimTest.gif)

**NEXT:**
- **Matchmaking and online services**
   - Tile generation will play a large role in matchmaking, as such I plan to implement a custom backend service for matchmaking
   - Otherwise other connection and social systems will use Steam Services
