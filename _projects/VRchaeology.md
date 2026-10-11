---
layout: post
title:  "VRchaeology"
summary: "PCVR,UE5,C++,Perforce,Team,Programmer"
preview: /assets/vrchaeology/VRch_preview.webp
image: /assets/vrchaeology/VRch_preview.webp
location: "stu/dio"
background: /assets/vrchaeology/vrch_background.webp
order: 2
---

![Title Image](/assets/vrchaeology/vrch_banner.webp)

### Overview
VRchaeology revolutionizes the study of archaeology by bringing archaeological field techniques into the classroom through virtual reality. This innovative approach allows students to delve into the world of archaeology and unearth the past right from their desks. It serves as a pioneering example of how VR can transform the education of field sciences, making hands-on learning accessible to everyone.

Project operating through stu/dio-a student led work-for-hire game development studio at the University of Illinois. Project sponsored by Dr. Laura Shackelford

### Development Details
**Platform/Engine:** Unreal Engine 5 for PCVR platforms

**Time:** Dec 2025 - Aug 2025

### Credits
* **Sponsor:** Dr. Laura Shackelford
* **Co-PI (NSF Grant):** Dr. David Wen-hau Huang
* **Associate Producer:** Sepehr Vaez Afshar
* **Project Manager:** Gabriel Wozniak
* **Additional Project Management Support:** Om Mistry, Pranav Shah
* **Engineering:** Anish Gupta, Praneeth Rangamudri, Nick Simons, Aashish Subramanian
* **Previous Engineers:** Zach Krauter, Ezra Schur, Gloria Xiao, Weijia “Charlie” Zhang
* **Design:** Madison Rosenberger
* **3D Art:** Nancy “Nan” Kang, Dominic Larrieu, Xiaoxu “Johnny” Lyu, Yiwen “Tiffany” Wu
* **Additional 3D Art Support:** Karan Ganesh, Mengzhen Yu
* **2D Art:** Synthia Cao, Pengkun “Daniel” Mao, Ruoheng Yang
* **Music:** Adrian Pawlikowski
* **Sound Design:** Aubree Gray
* **Voice Acting:** Olive Wang
* **Archaeology Content Support:** Emma Verstraete, Alexandra Zachwieja

### Highlighted Contributions

##### Code Review Integration

- Integrated Perforce's Helix Swarm code review tool into developer pipeline.
- Migrated project to trunk-based development workflow.

##### Quest and Action Signifier System

![Quest System Technical Design Document](/assets/vrchaeology/QuestSystem.drawio.webp)

![Example Quest Configuration](/assets/vrchaeology/ExampleQuest.webp)

<video src="/assets/vrchaeology/vr_quest_actionsignifiers.mp4" autoplay loop muted playsinline aria-label="Quest and Action Signifier System in Use"></video>

- Manages task templates and simple level scripting logic for the player, allowing designers to easily add action prompts and tasks to streamline level scripting and user experience.
- Directs player progression and guidance mechanisms for all 8 labs.

##### Dialogue Subtitle System

<video src="/assets/vrchaeology/vr_subtitle.mp4" autoplay loop muted playsinline aria-label="Dialogue Subtitle System"></video>

- Inspired by Half-Life Alyx, implemented system for tracking and managing dialogue subtitles to their sources within 3D space.
- Integrates with quest system to provide prompts and additional guidance to the player for tasks.
- Migrated and extended from Master Dancer system.

##### Digging and Stratigraphy Framework

![Stratigraphy System Technical Design Document](/assets/vrchaeology/StratigraphyTDD.drawio.webp)

<video src="/assets/vrchaeology/VRchVideo_1.mp4" autoplay loop muted playsinline aria-label="Digging Mechanic Demo"></video>

<video src="/assets/vrchaeology/VRchVideo_2.mp4" autoplay loop muted playsinline aria-label="Stratigraphy Layer Analysis Demo"></video>

- Implemented system allowing user to scrap and dig into surfaces using tools within the level to perform tasks like excavation and layer stratigraphy analysis.
- Developed method for monitoring player excavation progress in script through a compute shader.

##### OpenXR Hand Tracking and Gesture Detection for Quest Link

<video src="/assets/vrchaeology/vr_handtracking.mp4" autoplay loop muted playsinline aria-label="OpenXR Hand Tracking in Action"></video>

- Implemented reading and interpreting raw OpenXR hand tracking data through quest link for driving hand animations.
- Developed system for snapshoting gestures for recognition so designers can easily integrate them into gameplay actions.

### Gallery

<div class="video-max-wrapper" style="width: 100%; max-width: 800px; margin: 0 auto; aspect-ratio: 16 / 9;">
  <iframe 
    src="https://www.youtube.com/embed/m_5ZPABhV64" 
    title="VRchaeology Gameplay Edit" 
    frameborder="0" 
    allow="web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen=""
    style="width: 100%; height: 100%; display: block;">
  </iframe>
</div>

