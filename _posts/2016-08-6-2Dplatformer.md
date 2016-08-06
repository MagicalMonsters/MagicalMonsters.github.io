---
layout: post
title: 2D platformer
---


Back in 2011 Behdad and I started talking about games and game Ideas; the idea behind Elements was one of the first ones that he shared with me. It was born out of contemplating on social games like Mafia, and card games like Yu-Gi-Oh!. It was a board game but like Mafia it needed an omniscent entity to make it work and it had some complicated calculations so it couldn't be a traditional board game but a video game instead. 

<img src="http://magicalmonsters.github.io/images/2D.png" alt="image of our 2D platformer game" />

In its first iteration the game was designed for 2-4 players. The board was a diamond-shaped grid and each player had a number of warriors on this grid. There were four resources, namely air, earth, fire and water. Warriors were composed of a combination of these elements and the dominant element would have specified the warrior's type, and each type had a certain attribute, e.g., a warrior of type fire had more attack power and an earth warrior was good at defence. In each turn the player could move a warrior by one grid or attack a neibouring enemy or split the warrior into two warriors. The attack and defense logic was based on a graph indicated which element can attack which other elements. 

<!--more-->
