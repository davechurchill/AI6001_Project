# AI 6001 Project Specification

The final project for AI 6001 should be done in a group of 2 people. If there are any problems with your group members not doing their fair share of the work, you must see me immediately so that we can work out a solution while there is still time to do so. My observation over the years is that 99% of the time this happens, it is due to simple miscommunication between group members and can be solved with a few emails. If you wait until the final week before the project is due to come to me with group-related issues, there is probably nothing that can be done to help at that point. Everyone in this class is an adult, and part of the grade for this group project is your ability to work well with others to accomplish a shared goal.

## Marking Scheme

- **Project Demo** (20%)
  - A hosted version of the project that I can play to test the functionality
- **Project Code / Gameplay** (10%)
  - The final source code of the project that you have created
- **Project Report Video** (70%)
  - The final video explaining everything that is required in the specification below

### Project Overview
  - Must be implemented using ECS architecture in C++ using only the SFML / ImGui libraries
  - You may use any course code already written for assignments as the bases for your project game
  - Game Type Suggestions:
    - Platformer (MegaMan, Contra, Celeste, Shovel Knight)
    - Top-Down Shooter (Hotline Miami,  Enter the Gungeon, Brotato, Vampire Survivors)
    - Action RPG (Diablo, Zelda, Binding of Isaac, Path of Exile, etc)
  - No assets or levels may be re-used from the class assignments, and gameplay must be significantly different from assignments
  - Must contain at least 3 pre-built levels, and have a separate 'final boss' battle level
  -	Must contain a custom menu that allows the player to play the game, edit levels, or select options
  - Must contain some sort of in-game menu (item selection, inventory, options, etc)
  - Must contain a level editor that allows for loading, editing, and saving of game levels (see relevant section)
  - Must contain a ‘game over’ screen indicating when the game has been finished
  - All levels, player, and game configuration options must be defined in external text files
  - All assets should be gathered or created by the project group members

### Required Gameplay and Mechanics (From Assignments)
Your game must contain all the following mechanics. You may copy / paste / edit this list for use in your proposal. Your final project submission must contain this list which each finished feature marked as completed.
- [ ] Collisions
  - [ ] Rectangular bounding box collisions between some entities
  - [ ] Some collision between player and level geometry (walls, tiles, etc)
- [ ] Movement
  - [ ] Your game must contain at least 2 'movement abilitites' with a cooldown or resource cost
  - Our Game's Movement Abilities:
    - [ ] Example 1: Double Jump
    - [ ] Example 2: Dash (with invulnerability)
    - [ ] Example 3: Wall Jump
    - [ ] Example 4: Jetpack (with fuel)
     
## Project Report Video

Your project must contain a video report / presentation (approx 15-20 minutes) containing the following information:
- An overview of the game giving all details described in ‘Game Overview’ above, including asset sources
- A description of all `extra features’ put into the game on top of those specifically asked for
- Demonstrations of all game mechanics, with at least one full level playthrough. Also demo the level editor.
- Detailed list of controls for the game, and instructions on how to play / what the objectives are
- Notes on anything you tried to implement that did not end up working
- This video must contain audio commentary / explanation, and be uploaded to YouTube
- Post the report video URL to the main README for the project repo

