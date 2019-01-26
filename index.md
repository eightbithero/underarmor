---
layout: default
title: Under Armor - Homebrew NES game
---

# Under Armor
Homebrew NES game [download current build](files/rom/underarmor.nes)

<!--cut/
<video autoplay loop preload controls>
	<source src="images/video/demo.webm" type="video/webm">
	<source src="images/video/demo.ogv" type="video/ogv">
	<source src="images/video/demo01.mp4" type="video/mp4">
</video>
cut/-->

<video autoplay loop muted poster="images/video/demo.jpg?v1" controls="true"id="videodemo">
   <source src="images/video/demo.mp4?v1" type="video/mp4">
   <source src="images/video/demo.webm?v1" type="video/webm">
   <source src="images/video/demo.ogv?v1" type="video/ogg">
</video>

## About the game
The game is about exploring abyssal mazes. Every game session is unique based on level procedure generation. During the NES era there was no similar game. The main purpose of this project was to apply modern development approaches and gamedev practices to the old-fashioned gaming platform.

It was my childhood dream to make my own videogame. During 1980s-1990s in Russia the most common videogame console was a bootlegged version of NES called Dendy. The market was full of pirated Japan, European and North American releases. However not every game that existed was available. And i dreamt to make my own game one day. The most difficult parts of developing was to overcome video hardware limitations and to understand the principles of audio processing unit.

There were two approaches: the easy one that would have allowed me to use a high level language to write the game logic, but that would have produced surplus and slow binary code. The other one was to  write the code in pure asm to make the binary as small and efficient as possible, and to fill up the rest with media data. I wanted to use the same hardware that was availiable in NES era, without implementing an emulator on the cartridge. It was an interesting journey into the past, to find out how engineers at those times have done a lot of media effects that are common nowadays.

Play in good games.

### Current state
The game development is in process.
Looking for a good artist and musician.

### Worklog

- 21/12/2017
implemented binary tree algorithm for generating mazes
- 02/12/2017
"bulets" movement + sfx 
- 01/12/2017
sprite animation
- 24/11/2017
found out, that huge part of ordered tiles was stolen from other NES-project, cuted it out
- ../10/2017
- 27/09/2017
have been written utilities for converting images and tilemaps for internal NES format
- 25/09/2017
recieved graphics
- 01/09/2017
have ordered tiles and sprite graphics
- erlier
testing 6502 assemblers, utilities, collecting docs, first hello world for nes
