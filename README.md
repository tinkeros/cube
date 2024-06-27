# Cube
A Rubik's cube clone for TempleOS/TinkerOS

## Can you solve it?
<center><img src=https://raw.githubusercontent.com/tinkeros/cube/master/cube.gif></img>

## If no, at least you can smash it!
<img src=https://raw.githubusercontent.com/tinkeros/cube/master/smash.gif></img>

## Extensive help can be displayed along with cube for beginner learning
<img src=https://raw.githubusercontent.com/tinkeros/cube/master/help.png></center></img>

## Features
 - 20 difficulty levels 1-20
   - Level n means cube can be solved in n moves or less!
   - 20 is the max / God number. (all cubes can be solved in 20 moves or less if you are awesome!)
 - Hot keys implementing beginner algorithms to help make solving easier.
 - Outline of steps to solve the cube in a beginner layer by layer fashion.
 - Best number of moves/times are saved in the registry for each difficulty level.
 - You can re-play the same shuffled puzzle over again by including Cube.HC.Z and then running: ```CubeGame(difficulty,puzzle_number);```
 - On TempleOS/TinkerOS puzzle number 0 will call GodBits pop-up for you to generate a random puzzle number.

## Install
 - Copy Cube.ISO.C onto virtual hard drive and mount in OS (```MountFile("Cube.ISO.C");```) or place disc image in virtual CD drive.;
 - ```DirMk("C:/Apps");```
 - ```DirMk("C:/Apps/Cube");```
 - ```CopyTree("M:/Cube","C:/Apps/Cube");``` or T:/ instead of M:/ if in virtual CD drive.
## Run
 - ```Cd("C:/Apps/Cube");```
 - ```#include "Run"```
## Add icon launcher to personal menu
 - Open Icon.DD.Z
 - Copy icon (select all CTRL-SHIFT-arrows, CTRL-v)
 - Open personal menu (CTRL-m)
 - Paste into your personal menu (select spot, CTRL-v, CTRL-s to save)

<center><img src=https://raw.githubusercontent.com/tinkeros/cube/master/icon.png></center></img>

## Also can run on ZealOS with Cube.ZC
<center><img src=https://raw.githubusercontent.com/tinkeros/cube/master/zeal.png style="width: 640px;"></center></img>
