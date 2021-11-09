# IT266Wulf - Quake 4 Mod - Risk of Border Rain - Benjamin Wulf
# Caution: this mod contains strobe-like lighting effects and colors which may affect those with photosensitive epilepsy or other photosensitivities

## How To Play 

In this mod for Quake 4, a game was created taking inspiration from ones such as Risk of Rain 2, and the Borderlands series.
The player must collect powerups from enemy drops, as well as purchase weapons from loot drops from the marine entity that spawns on the bridge 
after the boss wave is killed (bosses spawn every 3rd wave). 
If the player wishes to buy the weapon from the marine/lootbox, they will simply left click while within talking distance.
If the player does not wish to purchase the weapon, simply take a step back until out of talking distance and kill the entity.
Within the game spawn, an initial monster entity is spawned for testing purposes, and the actual wave-based game begins after it is killed.
The monster Spawns are across the bridge inside the map.

## How To Download & Build 

In order to play this modified version of Quake 4, a copy of the game must be purchased separately (Can be obtained via Steam).

The Quake 4 Solution contains 3 Projects, Visual Studio Enterprise 2019 was used to build the solution.

Upon succesfully downloading Quake 4, and building the project, move the file "riskofborderrain.zip" into the "Quake 4" folder wherever it was installed
(default Steam path may look like Steam\steamapps\common\Quake 4)
Unzip the "riskofborderrain.zip" file here (7zip was used).

Although the gamex86.dll should be up to date within the mod folder, if the project is rebuilt with any changes, or if any issues occur, follow this process:

1. Build the project
2. Copy the newly created Gamex86.dll from within the "Debug" folder
3. Open the game000.pk4 compressed folder (7zip was used during this process)
4. Delete the gamex86.dll that already exists within it
5. Paste the Gamex86.dll file from step 2 into game000.pk4
6. Close game000.pk4
7. Run the game

If further issues occur, use shortcut to launch the game from within the folder, rather than using the steam launcher or other shortcuts
(the premade shortcut named "RiskOfBorderRain" will launch directly into the mod)



Goodluck, and enjoy!
