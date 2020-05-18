# MetalDetective
A metal detector simulator that allows you to search and dig for treasure on a beach.

## Attributions

Background sound track:
wave close coast small LONG by klankbeeld
https://freesound.org/s/433983/

Menu button graphic:
Taken from Island Game GUI by Free Game Assets (GUI, Sprite, Tilesets)
https://free-game-assets.itch.io/free-game-user-interface

Gold and Timer HUD icons:
Icons made by Smashicons from www.flaticon.com
https://www.flaticon.com/free-icon/ingot_138540
https://www.flaticon.com/free-icon/clock_148932

Palm tree model:
Based on "palm tree modeling in autodesk maya" by Daniyal-Environmental Artist
https://www.youtube.com/watch?v=DZaV7xcoLFc

## Description

This game is a metal detector simulator, originally created as part of the Game 
Programming and Development coursework at Southern New Hampshire University. In the game, 
the player must use a metal detector to search a beach for hidden treasure within a time 
limit. A dig ability is included to allow the player to reveal the treasure after the 
detector has indicated it is nearby through a combination of sound and visual cues.

## Tools Used

- Unreal Engine 4
- Autodesk Maya
-Autodesk 3ds Max
- Adobe Photoshop
- GIMP

## Reflection

How would you describe the process of creating and polishing the artifact?

The process of creating and polishing the artifact was very iterative. First the 
landscape mesh was made using the landscape tools in Unreal Engine 4. Next, the 
dig functionality was built which allowed the mesh to be altered in-game to simulate 
digging terrain. The random spawner then had to be implemented to allow the treasure 
to spawn dynamically within a defined space just below the surface of the ground. 
With all of the basic functionality present, other elements, such as models and HUD 
elements, were added. Finally, a timer and score system were created to give the 
player a goal while playing the game. The refinement process involved improving the 
map layout and adding background music to better immerse the player. A menu system 
was also included to allow the player to view instructions and navigate between the 
main menu and game level.

What did you learn as you were creating it and improving it?

The first version of Metal Detective was the first game I created with a clear 
objective and a win/lose condition. I learned how take a game idea and implement 
the code so that it functions as a playable game. To make it more appealing, I 
developed three-dimensional models in Autodesk Maya to help build a believable world. 
It was very basic and as I refined the piece I tried to build upon this foundation 
and develop a game that incorporated some of the new skills I had picked up. I used 
3ds Max to create a metal detector model and added a dynamic material to allow the 
indicator to flash in-game in conjunction with the sound cue.

What challenges did you face?

The main challenge I faced when refining this piece was having to revisit a project 
and figuring out how I had organized various aspects of the game. Now that I am more 
comfortable with Unreal Engine development, I have learned some of the standards and 
am able to better organize my work. Also, I was unable to get the character animations 
to mix with the metal detector during the refinement phase. This was due to a lack of 
experience and time constraints. To overcome this issue, the character is hidden in 
the updated version.

How did you incorporate feedback as you made changes to the artifact?

The feedback received from the first version of Metal Detector mainly focused on the 
structure of the game while the player is searching for treasure. There was no clear 
goal or end condition, meaning that the game was very boring and could last for a long 
time. This led to some changes that ensured the player knew exactly what their objective 
was and set a clear limit to how long the game would last.

How was the artifact improved?

- Rebuilt the landscape mesh and assigned it to the beach component
- Created a larger level and rearranged the environmental components
- Created a model for the metal detector in 3ds Max and assigned a dynamic material to give visual feedback to the player
- Adjusted the detector collision to compensate for the new model
- Added a background track to the level
- Created a main menu, pause menu, and game over menu with button graphics
