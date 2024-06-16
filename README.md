# Hiken - Browser Battle

## Overview

Hiken is a browser-based 2D fighting game where players can engage in thrilling battles using various characters and abilities. This game offers both single-player and multiplayer modes with unique attacks and special abilities for each character.

## Instructions

This application allows users to play a 2D fighting game directly in their browser. Follow the instructions below to get started and control your characters.

## Controls

### Player (Left)

- **Movement**: Use the 'W', 'A', and 'D' keys.
- **Attack**: Press 'Space Bar' to attack.
- **Special Attacks**:
  - Healing effect: Press 'X'
  - Melee attack: Press 'C'
  - Ranged attack: Press 'Z'

### Enemy (Right) (Automatic by default)

- **Movement**: Use 'Arrow Up', 'Arrow Left', and 'Arrow Right' keys.
- **Attack**: Press 'Enter' to attack.
- **Special Attacks**:
  - Healing effect: Press 'Arrow Down'
  - Fireball: Press 'P'

## Attack Simulation

- The attack simulation function, `simulateAttack()`, can be found in the [enemy.js](./js/enemy.js) file.
- This function uses random numbers to simulate attacks and can be adjusted to change the game's difficulty.
- To increase the probability of enemy attacks, expand the range of the conditional statements in the simulation function.

## Preview

![Start_Image](/screenshots/Start_Screen_White_BG.png)
![Character_Selections](/screenshots/Character-selections.png)
![Background_Selections](/screenshots/Background-selections.png)
![Fight_Scene_1](/screenshots/Battle1.png)
![Fight_Scene_2](/screenshots/Battle2.png)

## Live Demo

Check out the live demo of the game deployed on GitHub Pages: [Hiken](https://edwinperaza99.github.io/Hikken/)

## Team Information

- Edwin Peraza: edwinperaza@csu.fullerton.edu
- Spencer Price: spencerprice@csu.fullerton.edu
- Joji Thomas: jthomas@csu.fullerton.edu
- Ethan Marcelino: emarcelino@csu.fullerton.edu
- Nghia Phan: ptnghia@csu.fullerton.edu
