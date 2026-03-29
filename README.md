# Shark's Diablo2 Ladder-mod

## Installation notes:
 1) fork/download and put in a Ladder-Mod folder in your Diablo2 folder.
 e.g. ***\Games\Diablo II\Ladder-Mod
 2) Make a new shortcut with "Target:" `"***\Games\Diablo II\Diablo II.exe" -direct -txt` and "Start in:" `"***\Games\Diablo II\Ladder-Mod"`
 3) the `***` is the drive and full path to the Diablo2 folder
 4) run the shortcut, happy gaming.

## Features:
 - no more ladder-locked stuff.
 - all ladder-only recepies and items are unlocked, and available
 - hireling rework, consult docs/
 - new cube recepies, consult docs/Ladder-Mod Cube Recepies
 - "Jewel crafting" system, consult docs/Ladder-Mod Cube Recepies

### "Scope creep" Features
A few more features slipped in, mainly concerning two particular builds which are also "borrowing" inspiration from Diablo 3 and some of my realm grievences.

 - The Druid "beastmaster" build: animals no longer replace each other, and can all be summoned at the same time. Adjusted limits to:
	- Ravens: 			13 (up from 5 at level 20)		- new formula is `(lvl < 6) ? lvl :(3+(lvl/2))`
	- Spirit Wolves: 	7  (up from 5 at level 20)		- new formula is `"min( (1+(lvl/3)), par3)"`
	- Dire Wolves:		5  (up from 3 at level 20)		- new formula is `"min( (1+(lvl/4)), par3)"`
	
	tl;dr - ravens are no longer capped, both wolf caps have been increased by +2.

 - The Necromancer "golemer" build: golems no longer replace each other, and can all be summoned at the same time. Iron golem is still the one that is saved into the savegame.

 The new "gem breaking" cube recepies are technically also 'scope creep' but mainly have to do with the fact that upgrading runes will require e.g. chipped gems, and you don't
 get to see many of them at higher level / higher difficulty plays anymore.

### Future ideas:
 - expand a bit more on the 'jewel crafting' system, so that the player can create non-class skill based jewels with a somewhat precise picking/choosing system.