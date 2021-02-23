1. Set up for the game was pretty basic. I downloaded the assets, deleted the scenes, and created my own scenes using the prefabs available. 

2. As stated above, I deleted the main and secondary scenes that were in the project by default. I then created my own scenes called Level 1, Level 2, and Level 3. I added those to the build settings and modified the level transitions to proceed successively. The order goes Intro -> Level 1 -> Level 2 -> Level 3 -> Win/Lose.
Every level has at least 5 areas in which enemies spawn. These sometimes include different items or powerups. 
A KSU logo appears in every level, in slightly different fashions. The first level presents two holographic pyramids that display the KSU K with "Kent State" underneath. Other levels display billboards. Additionally, the tall statue is modified to the Kent State logo as a texture. 
Floor and wall textures are basic grass, dirt, glass, and other simple textures. 
Lighting conditions are different in each level, however they all use the directional lighting. The directional lighting uses different intensities, different colors, and different angles in each map.

3. For the difficulty setting, "Easy" is default. There's nothing special about Easy mode. Hard mode increases enemy HP pools by 2.5x, increases the damage the player takes by 1.5x, and introduces a power up that the player can find throughout each of the map that will both restore his/her HP and increase the max HP values by double. By the end of the third level, the player can increase his/her total HP to a substantial level to even the odds. 
The difficulty setting here is handled in a very simple way: Instead of coding a button to change how enemies behave, the levels are duplicated to allow for extensive modification. Hard mode maps feature higher enemy counts as well as extended areas to explore. 
My desired effect for hard mode was to include a power up to changes the player's damage output. However, with the way the project is coded originally, it was too difficult to tell exactly how to handle this idea in the short amount of time allocated to this project. 

4. Notes are put in each script added (teleportation, power up). 

5. Along with the power up mentioned above for hard mode, teleportation is added in as a feature for level 1 and level 3, in both easy and hard difficulties.

2/16/2021 Edit: I added a new feature thanks to the extended time given due to the snow storm. I added a feature where the player can dash a distance when the sprint button (left shift) is pressed. This allows for quicker and skillful movement by the player.