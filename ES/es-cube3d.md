---
title: cub3d
description: 'Este projecto esta inspirado en el famoso juego de los 90 doom y en su algoritmo grafico, RayCasting.'
img: 'cube3d.jpg'
url: 'es-cube3d'
git: 'https://github.com/JavierCervilla/Cube3D.git'
---
Este projecto esta inspirado en el famoso juego de los 90 doom y en su algoritmo grafico, RayCasting.
El objetivo del proyecto es recrear el motor grafico utilizando para ello la minilibx.
## Un poco de Historia
Developed by Id Software by the über famous John Carmack and John Romero, published in 1992 by Apogee Software, Wolfenstein 3D is the first true “First Person
Shooter” in the history of video games.

Wolfenstein 3D is the ancestor of games like Doom (Id Software, 1993), Doom II
(Id Software, 1994), Duke Nukem 3D (3D Realm, 1996) and Quake (Id Software, 1996),
that are additional eternal milestones in the world of video games.
If you want to know more :arrow_right: [Wolfenstein 3D](https://es.wikipedia.org/wiki/Wolfenstein_3D)

## Pre-requisites
- [x] Linux OS
- [x] GCC Compiler

## Installation
1. `git clone https://www.github.com/JavierCervilla/cube3D.git`
2. `make` or `make bonus`
3. `./cub3D maps/mandatory.cub` or `./cub3D_Bonus maps/tx.cub`

Based on your `make` choice, you should use one map or another.

## Controllers

- WASD to move through the map
- KEY_LEFT & KEY RIGHT to rotate the camera


### Resources :book:
+ [Permadi Raycasting Tutorial](https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)
+ [Minilibx Info](https://qst0.github.io/ft_libgfx/)
+ [Lodev Raycasting Tutorial](https://lodev.org/cgtutor/raycasting.html)
+ [Creating BMP Images](http://ricardolovelace.com/creating-bitmap-images-with-c-on-windows.html)