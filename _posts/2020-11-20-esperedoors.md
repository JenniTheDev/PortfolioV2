---
title: "Espere's Journey - Doors, Doors, Doors"
date: 2020-11-20
permalink: /posts/2020/11/esperedoors/
tags:
  - espere
  - unity
  - gamedev
---


I had thought I had worked out the door puzzle problem in [my previous post](https://jennithe.dev/posts/2020/11/esperepuzzles/), but they weren't working as well as I wanted. It also seemed really unnecessary to be using keys to open the door when we weren't giving the player any sort of key. 

Plus there were other problems. If an enemy stood on a trigger, it would cause the door to open or do some unexpected behavior. The player could walk over the trigger and trigger it multiple times. The entire system couldn't be reused on different doors without bugs. My doors also needed audio and animations. The engineer in me never considered the doors would need animations, not just simply being open or closed. I want to keep my designers happy, so I reworked my doors into an entirely new and improved system.  

After talking it over with the designer and some other developers, I decided to make a class, Door. Then my different types of doors can inherit from the Door class. The Door class handles opening the door and checking the key if needed. That way I can use it on doors that just need to open, or need triggers to open, or need a specific set of triggers in order to open. 

<Put a little code snip here>

<Some more stuff about the different types of door types, interface>

<a giphy with the music sound door>

<wrap it up, conclusion, link to git>
