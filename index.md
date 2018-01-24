---
layout: default
title: Under Armor - Homebrew NES game
---

# Under Armor
Homebrew NES game [download current build](files/rom/underarmor.nes)

<video src="images/video/demo01.mp4" autoplay loop preload></video>

## About the game
The game is about exploring abyssal mazes. Every game session is unique based on level procedure generation. During the NES era there was not any simillar game. The main purpose is to apply modern development approaches and gamedev practices to the old fashioned gaming platform.

Childhood dream has driven me to make this project alive. During 1980s-1990s in Russia the most common videogame console was bootlegged version of NES called Dendy. The market was mixed up with pirated Japan, Europe and North America releases. However not every game that exists was available. And i have dreamed to make my own game one day.
The most difficult parts of developing were an overcoming of video hardware limitations, and an understanding of audio unit principles of this architecture.

There was two approaches: easy one that will allow me to use high level language to write logic, but will produce surplus and slow binary code, or write it in pure asm to achive the small as possible and efficient binary, and fill up the rest with media data. I wanted to use same hardware that was availiable in NES era, not implementing emulator on a cartridge.
It was interesting journey into the past, to find out how engineers at those time have done a lot of media effects that are common nowadays.

Play in good games.

## Current state
The game development is in process.
Looking for a good artist and a musician.

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
