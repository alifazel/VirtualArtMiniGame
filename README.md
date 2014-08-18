# VirtualArtMiniGame

## Description 
A mini-game embedded into a virtual enviroment, rendered using Blender Game Engine. The purpose of this mini game is to demonstrate the art work ‘The Gaia’ by Jussi Loff. It follows an adventure that is built upon interpretation of the art work. 

## Instructions for Use
In order to use this artwork project, start the game using the blender file ‘RunGame.Blend’. Set the initial starting scene to ‘Splash’ and make sure the camera is set ‘Start Cam’, or press [Numpad 0]. 
Using the Render Preferences tab, you can change the visual settings of the game to suit the system being used. The resolution can be set using the Width and Height fields in the standalone player. Advanced options to Bit Depth and Anti-Aliasing can also be changed. When ready, the game can then be started using the ‘Start’ Button in the same standalone player settings.
Recommended Settings: Width = 640, Height=480, FullScreen=On

## Controls
The Main Menu is navigated using the cursor keys to select the different menu options and selected with the [Return] Key.
The Actual game controls are displayed on-screen before the start of the game, but can be summarised as following:
[A] Move Left
[D] Move Right
[Mouse Movement] Look around
[Left Mouse Click] Shoot bullets.

## Main Architecture (In Order):
* Splash Screen – The initial starting scene for the game, displays the starting graphic to the user.
* Main Menu – A menu scene that allows you to either start or end the game
* Control Screen – A scene that displays the controls of the game to the player.
* Room – Initial automated starting scene that plays when the user starts the game. Displays the start where the player is shown slightly disorientated and takes drugs to further go under the influence. This causes the player to then blackout.
* Main Game – The main game where the player is to shoot the bubbles that originate from the face mask.
* Art Work – This scene displays the actual artwork to the user.
* BG_Music_Scene – A background scene that is displayed that creates an overlay music.
