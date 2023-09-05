# Sonar-Treasure-Hunter - A Treasure Hunting Game

## Introduction
A treasure-hunting game where you take on the role of the captain of the Simon, a treasure-hunting ship. Your mission is to use sonar devices to locate and retrieve three sunken treasure chests at the bottom of the ocean. However, the catch is that you only have cheap sonar devices that provide distance information, not direction.

## Instructions
1. Enter the coordinates to drop a sonar device. The ocean map will display how far away the nearest chest is, or an X if it's beyond the sonar device's range.
2. The ocean map initially shows you where the chests are located, marked as C, but in the actual game, the chests are hidden.
3. When you drop a sonar device directly on a chest, you retrieve it, and the other sonar devices update to show the distance to the next nearest chest.
4. Sonar devices can detect treasure chests up to a maximum distance of 9 spaces.
5. Your goal is to collect all 3 chests before running out of sonar devices.
6. You start the game with 20 sonar devices and must strategically use them to locate the treasure chests.

## Example Gameplay
Here's an example of how the game is played:

                 1         2         3
       012345678901234567890123456789012

     0 ~~~~`~```~`~``~~~``~`~~``~~~``~`~ 0
     1 ~`~`~``~~`~```~~~```~~`~`~~~`~~~~ 1
     2 `~`C``3`~~~~`C`~~~~`````~~``~~~`` 2
     3 ````````~~~`````~~~`~`````~`~``~` 3
     4 ~`~~~~`~~`~~`C`~``~~`~~~`~```~``~ 4

       012345678901234567890123456789012
                 1         2         3


## Goal
Collect all 3 hidden treasure chests using your sonar devices before you run out of devices.

Enjoy the hunt and best of luck in uncovering the sunken treasures!

