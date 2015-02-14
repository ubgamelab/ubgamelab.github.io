---
layout: project       #important: don't change this
title:  "Tactical Pathfinding Algorithm for Non-Player Character in 3D Game"
year: 2013
author: Iqra Ahmadya
categories:
- project             #important: leave this here
img: tactical-pathfinding.jpg #place image (600x450) with this name in /assets/img/project/
thumb: tactical-pathfinding.jpg
carousel:
- tactical-pathfinding.jpg        #place image (1280x600) with this name in /assets/img/project/carousel/  

supervisor: Eriq M. Adams J, Himawat A.
preview: http://www.youtube.com
---
####Tactical Pathfinding Algorithm for Non-Player Character in 3D Game.
Pathfinding is one of the implementation of artificial intelligence in games. Shortest pathfinding is a matter that affects non-player character movement and decision making. However, shortest path does not mean and does not always the safest path. In a military-based game, character be charged to move and making decision tactically. When agents move tactically, they are not only seek for the shortest path, but the agents must consider the threat since there any hit points consideration, for the sake of increasing the reality matter in game.
Tactical Pathfinding is a one of pathfinding algorithm that can implement shortest pathfinding with considering weights treat. The implementation of tactical pathfinding can provide non-player character with tactical movement. Tactical pathfinding is implemented based on A* pathfinding with weights threat addition.
The algorithm implemented with doing a simulation on 3D navigation mesh based game maps. Game maps will represent in 3D navigation mesh, because navigation mesh become the primary world representation in recent years. Algorithm is implemented by giving the navigation mesh region with threat weight, so that it change the agent pathfinding decision to find a goal. Algorithm is implemented in 3 different simulation scenarios. Simulation will be implemented in Unity game engine version 3.5.
Frame-rate testing of the 20 test in 3 simulation scenario shows that tactical pathfinding algorithm using more memory than traditional shortest pathfinding, although it is not very significant. Whereas, in hit points testing in 15 simulation scenarios, shows that tactical pathfinding can reduces the damages received by the non-player character agent although it is not very significant.
