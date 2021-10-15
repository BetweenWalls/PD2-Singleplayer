# PD2-Singleplayer
This collection aims to include everything you'd want for singleplayer testing in [Project D2](https://www.projectdiablo2.com/).

### [Download](https://github.com/BetweenWalls/PD2-Singleplayer/archive/main.zip)

## Inclusions
* level 99 characters for each class with accurate stats and skill points (level 30 & level 90 characters in subfolders)
* all unique/set items
* PD2-specific items (maps, worldstone shards, puzzleboxes, dclone materials, etc.)
* stacks of all runes/gems
* variety of jewels/charms
* examples of all runewords, and additional item bases for making your own
* some magic, rare, and crafted items
* all regular items

## Setup Guide
The singleplayer PlugY mod adds stash pages for all the items. A copy of [PlugY 11.02](http://plugy.free.fr/) is included in the files.

1. Install Diablo II LoD
2. Install PD2
3. Install PlugY
* * copy PlugY.dll, PlugY.exe, PlugY.ini, and the PlugY 'readme' text file to your *Diablo II\ProjectD2* directory
* * copy the PlugY folder and its contents (11 files) to your *Diablo II* directory
4. Install this collection
* * Replace PlugY.ini in your *Diablo II\ProjectD2* directory with the version included here
* * Copy the files from the included Save folder to your *Diablo II\Save* directory
5. Run PD2 as you would normally to get the latest patch/update
6. Run PlugY.exe as administrator

If you need to revert to an older version of PD2 (to drop maps or other incompatible items) you can use the patch_d2.mpq files included in the *Patches* folder. I've also made a character converter that can update your older character files to the most recent season: [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-character-converter-for-pd2)

If you also want to install Basemod, see this [reddit post](https://www.reddit.com/r/ProjectDiablo2/comments/otnk61/season_3_single_player_plugybasemod_item_pack/) by Swoosh. Switching to a different item pack is as easy as copying the desired *_LOD_SharedStashSave.sss* to your *Diablo II\Save* directory.

## Stash Organization
The shared stash has multiple pages and can be navigated in increments of 1, 10, or 100 pages at a time. The stash is organized as follows:

* (1-9) **Common Stuff**
* * empty page (for dumping items quickly or storing whatever's currently being tested)
* * workstation (runes, gems, uber materials, corrupting materials)
* * maps
* * crafting jewels, rejuvs, quest items, etc
* (10-19) **Unique Jewelry & Example Items**
* * unique amulets/rings/jewels/charms
* * useful magic jewels
* * magic, rare, & crafted items
* (20-29) **Uniques - Class-Specific**
* (30-49) **Uniques - Armor**
* (50-79) **Uniques - Weapons**
* (80-89) **Sets**
* (90-99) **Runewords - Armor**
* (100-109) **Runewords - Weapons**
* (110-139) **Charms**
* * resistance, damage, and mana charms
* * skillers for each class
* * various testing charms
* (140-149) **Base Items**
* (150-169) **Random Magic Items for Crafting**
* (170-199) **All Regular Items**

There are in-game commands for renaming stash pages and moving stash pages around - checkout the PlugY readme.

## Editing
The included blank characters can be edited with [Hero Editor](https://www.moddb.com/games/diablo-2-lod/downloads/hero-editor-v-104) or other editors, but only until they're loaded in-game. Once you play a character and save it, the character's file will be formatted differently. If you're making many edits, create copies of the unplayed character files before entering the game with them.

Note that while most statlines can be edited normally, some have been changed in PD2 and will prevent the character from loading properly.
