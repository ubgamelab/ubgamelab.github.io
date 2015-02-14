---
layout: project       #important: don't change this
title:  "Real-Time Pathfinding on Computer Game Using A* and Reynold Steering Obstacle Avoidance"
year: 2015
author: Ivan Ananda Harsono
categories:
- project             #important: leave this here
img: realtime-pathfinding.jpg #place image (600x450) with this name in /assets/img/project/
thumb: realtime-pathfinding.jpg
carousel:
- realtime-pathfinding.jpg        #place image (1280x600) with this name in /assets/img/project/carousel/  

supervisor: Eriq M. Adams J, Issa Arwani.
preview: http://www.youtube.com
---
####Real-Time Pathfinding on Computer Game Using A* and Reynold Steering Obstacle Avoidance.
A * algorithm is a traditional algorithms that are often used to solve the problem of pathfinding. Traditional long steering algorithms such as A* is not able to be used to solve real-time pathfinding problems. Real-time pathfinding is a pathfinding problems in real-time environment where there is a dynamic obstacle that increase the complexity of pathfinding. With traditional A* in real-time environment, if there is a dynamic obstacle there will be a recalculation path that will take a lot of CPU resources. One of the short steering algorithms that can be applied to solve real-time problems pathfinding is Reynolds Steering Obstacle Avoidance who was able to avoid any collision with dynamic obstacles. Therefore, in this study implemented a real-time pathfinding algorithm that integrates long steering A* algorithm for pathfinding and short steering Reynolds Steering Obstacle Avoidance algorithm to avoid any collision with dynamic obstacles so it does not need to re-calculate path to optimize the performance of the CPU.
The algorithm implemented by doing a simulation on a 3D game map. Representation of the search space of a game map is using a square-shaped regular grids. On the map, will be placed some dynamic and static obstacle then there’s will be an agent that will run from the starting point to a destination point on a path that has been calculated and agen will avoid obstacles. Simulation of algorithm implementations will be divided into 2 scenarios. Simulations done with the game engine Unity version 4.6. Testing the path length in 30 trials in scenario 1, shows that the real-time pathfinding implementation using A* and Reynolds Steering Obstacle Avoidance will result in a longer path than path re-calculation with a ratio of 8:7. As for FPS testing on 30 trials in scenario 2, shows that the performance of the CPU in the real-time pathfinding implementation using A* and Reynolds Steering Obstacle Avoidance would be 2 times more optimal than path re-calculation.
