---
layout: post
title:  "VRchaeology"
summary: "Programmer"
preview: /assets/VRch_preview.png
background: /assets/vrch_banner.png
order: 2
---

![Title Image](/assets/vrch_banner.png)

**Overview:**
VRchaeology revolutionizes the study of archaeology by bringing archaeological field techniques into the classroom through virtual reality. This innovative approach allows students to delve into the world of archaeology and unearth the past right from their desks. It serves as a pioneering example of how VR can transform the education of field sciences, making hands-on learning accessible to everyone.

Project operating through stu/dio-a student led work-for-hire game development studio at the University of Illinois. Project sponsored by Dr. Laura Shackelford

**Platform and Engine:**  
   Unreal Engine 5 for PCVR platforms

**Team Structure:**  
   12 Members:
   - 1 Project Manager
   - 4 Programmers
   - 1 Designer
   - 4 Artists
   - 1 Sound Designer
   - 1 Music Composer


**My Work:**
-  **Code Review Integration**
   - Integrated Perforce's Helix Swarm code review tool into developer pipeline.
   - Migrated project to trunk-based development workflow

![Quest System TDD](/assets/QuestSystem.drawio.png)
![Quest System TDD](/assets/ExampleQuest.png)
![Quest/Action Signifier System](/assets/vr_quest_actionsignifiers.gif)
-  **Quest and Action Signifier System**
   - Manages task templates and simple level scripting logic for the player, allowing designers to easily add action prompts and tasks to streamline level scripting and user experience.

![Dialogue Subtitle System](/assets/vr_subtitle.gif)
-  **Dialogue Subtitle System**
   - Inspired by Half-Life Alyx, implemented system for tracking and managing dialogue subtitles to their sources within 3D space.
   - Migrated and extended from Master Dancer system.

![Stratigraphy System TDD](/assets/StratigraphyTDD.drawio.png)
![Digging](/assets/VRchVideo_1.gif)
![Stratigraphy](/assets/VRchVideo_2.gif)
-  **Digging and Stratigraphy Framework**
   - System allowing user to scrap and dig into surfaces using tools within the level to perform tasks like excavation and layer stratigraphy analysis.
   - Developed method for monitoring level progression in script through compute shader.

![Quest System TDD](/assets/vr_handtracking.gif)
-  **OpenXR Hand Tracking and Gesture Detection for Quest Link**
   - Implemented reading and interpreting raw OpenXR hand tracking data through quest link for driving hand animations.
   - Developed system for snapshoting gestures for recognition so designers can easily integrate them into gameplay actions.
   