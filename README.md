# SME-Assignment
# SME-Assignment

## Part1: Setting up your Project 
It Took me only 15 min to setup the project. I have made the following changes:
Copy pasted the inclde and lib in the `smfl` folder.

## Part2: Bug Fixing
Fixed the bug in the code. The bug was in following file: Took me only 3 hours to fix the bug.
1. Space-Invaders/header/Gameplay/HighScore.h
	   on line number 12, previously it was 
    `static class HighScore
    {


    changed it to

    `class HighScore
    {

2. Space-Invaders/header/Player/PlayerModel.h
    changed line 57 from 
   `static const int invincible_player_alpha = 170.f;`
    to
   `const float invincible_player_alpha = 170.f;`


   //Although i don't have that much idea of game development but I tried my best resolve the bugs and contributed as much i can using gathering resources and watching 
    vedious from youtube 

## Part3: Small Improvements 

I have made a Bullets folder in Space-Invaders/source/Bullets and build a two cpp file BulletsService.cpp and BulletsSystem.cpp

I have made the .h files of Bullets folder inside the Space-Invaders/header/Bullets/
these .h files are used in BulletsService.cpp and BulletsSystem.h

//I have tried my best to reach the outcome you are wishing for.

