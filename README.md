# PawPrints-Home
A 2D maze exploration game where the player follows clues to find a lost cat.

Link to PawPrints Home in MakeCode Arcade
https://arcade.makecode.com/S22505-80512-06885-08887

## Table of contents

- General Information
- Technologies Used
- Features
- Screenshots
- Setup
- Usage
- Project Status

## General Information
- About the game: Pawprint Home was created with Microsoft MakeCode Arcade. The player explores a maze, follows paw prints, looks for a collar, and speaks to a neighbor to find a lost cat. Some paw prints lead to dead ends, encouraging the player to explore different routes.
- Purpose: The project uses a simple search game to explore the theme of missing pets and community help.
- Motivation: I chose this project because of my interest in animals and pet safety. I also wanted to learn how programming and clues can shape player interaction.

## Technologies Used
- Microsoft MakeCode Arcade
- Python and blocks
- Sprites, tilemaps, controller input, and overlap events

## Features
- A maze map with different routes and dead ends.
- Paw-print and collar clues.
- A neighbor NPC who provides a directional hint.
- A camera that follows the player.
- A victory message, sound, and visual effect.

## Screenshots
- Exploration and Clues: The player explores the maze and looks for paw prints and a collar.
  
  <img width="1341" height="511" alt="截屏2026-10-28 18 30 14" src="https://github.com/user-attachments/assets/495d491b-d2bd-4805-99ff-2d13498d21df" />

- Neighbor Dialogue: The player speaks to a neighbor to receive a hint.
  
  <img width="1341" height="511" alt="截屏2026-10-28 18 30 00" src="https://github.com/user-attachments/assets/d39b5e77-29f2-4c31-85c7-4dcc3cf04972" />

- Winning Screen: The game displays a victory message when the player reaches the goal.
  
  <img width="1341" height="511" alt="截屏2026-10-28 18 30 26" src="https://github.com/user-attachments/assets/c6d96f8a-fa74-4024-beed-c1b8d28f7cc3" />

## Setup
The game can be played in a web browser without installing additional software.

- Open the game link in the Play the Game section.
- Wait for the MakeCode Arcade simulator to load.
- Select the on-screen A button to advance through the opening screens.

## Usage
Use the arrow keys to move around the maze and search for the lost cat.

- Follow paw prints and look for the collar.
- Explore alternative routes when clues lead to dead ends.
- Move up to the neighbor to receive a hint.
- Select the on-screen A button to advance through the dialogue.
- Reach the goal near the cat to trigger the victory screen.

The following Python code enables directional movement and makes the camera follow the player
- controller.move_sprite(mySprite)
- scene.camera_follow_sprite(mySprite)

## Project Status
- The prototype is complete.

## Room for Improvement
Possible improvements for future versions:

- Refine clue placement through further playtesting.
- Add more NPC dialogue and additional maze levels.

## Acknowledgements


