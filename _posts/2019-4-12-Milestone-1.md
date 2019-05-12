---
layout: post
title: Milestone 1
---

For our first milestone, we were able to get a rudimentary implementation of static obstacle avoidance working. We used the camera mounted
on the car to detect the largest region of free space to navigate towards, and once this is found we change the steering angle accordingly.
This implementation doesn't take into account moving obstacles and assumes a constant velocity for our car. There are some limitations we 
are encountering however. First, the camera we are using cannot detect objects that are less than a certain threshold distance in front of 
it, which is approximately a foot. This means that as we get close to an object, the car eventually loses track of objects nearby which 
messes up avoidance. Below is an image of a depth cloud obtained with the camera which is one of this things we use to calculate the new 
trajectory of the car. 

![_config.yml]({{ site.baseurl }}/images/depth.png)
