# Astro Party

## Overview

University of Texas EE319K Game Design Lab

We recreated a popular iOS mobile game called [Astro Party](https://itunes.apple.com/us/app/astro-party/id904693943?mt=8) on the EK-TM4C123GXL Launchpad.
Astro Party is a 1v1 game in which each player controls their spaceship and shoot each other. 

### Basic Rules
Your ship is always accelerating in the direction it is currently facing
Your ship can only rotate one direction with a button press (clockwise or counter-clockwise)
Each ship has a maximum of 3 bullets (bullets reload after active ones explode)
A round ends when one of the ships is destroyed
A point is earned by destroying the opposing ship
The first to reach the point cap is the winner

## Features

### Software:
* Two-player game
* Physics Engine
  * Collision Detection
    * Hitbox Collision Detection
    * Linear Per-pixel Collision Detection
  * Velocity 
  * Acceleration
* Gameplay modes
  * Adjustable Game Length (1,3 or 5 kills)
  * 3 Unique Maps
* Graphics Rendering
  * Virtual Buffer
  * Layered Graphics
* Edge-Triggered Interrupts
  * Pause game

### Hardware:
* Three Onboard Buttons (reset, start, and select)
* Four Buttons (two for each player)
  * Shoot
  * Rotate ship
* ADC Slider
  * Navigate game menu (settings)
  * Volume control
* 8-bit DAC
  * Sound effects
* Sitronix ST7735R LCD

## Demo

### EE319K SuperFinals Game Competition:

[<img width="300" alt="competition" src="http://img.youtube.com/vi/ogT-apOq7TE/1.jpg">](https://youtu.be/ogT-apOq7TE)

## Screenshots

<img width="213" alt="gathr screenshot" src="https://user-images.githubusercontent.com/16355946/35762693-ec45b69c-0860-11e8-8682-20cc0c9211ae.png"><img width="657" alt="prototype" src="https://user-images.githubusercontent.com/16355946/35762571-3855235e-085e-11e8-99c8-4fe74ef209d6.png">

## Built With

* [C](https://en.wikipedia.org/wiki/C_(programming_language)) - Programming language
* [Keil uVision IDE](http://www2.keil.com/mdk5/uvision/) - IDE for embedded software development

## Authors

* **Brian Cheung** - Game engine and physics engine
* **Sam Wang** - Sound module and sprites

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* We do not own any of the Astro Party UI desgns, concepts, logos, etc. Rusty Moyher owns these UI designs, concepts, logos, etc.
* Code snippets and boilerplate code from:

  "Embedded Systems: Real Time Interfacing to Arm Cortex M Microcontrollers", ISBN: 978-1463590154, Jonathan Valvano, copyright (c) 2015 

  belong to Jonathan Valvano. I do not take credit for code snippets and boilerplate code from the textbook.
