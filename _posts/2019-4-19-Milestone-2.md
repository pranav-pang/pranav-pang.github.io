---
layout: post
title: Milestone 2
---

For our second milestone, since we were having many setbacks with using the camera for obstacle avoidance, we switched to using the Lidar
sensor onboard the car. The Lidar works by sending out pulsed lasers in different directions and outputs an array of distances that    represent the distances to various objects at different angles relative to the car. Naturally, the larger the distance value the farther 
away an object is, so from this data we want to find the largest region of free space and navigate the car towards there. The video below 
shows a simulation of our efforts for this milestone. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/3kv4FkOpkhc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
