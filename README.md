# PD2-Singleplayer
This collection aims to include everything you'd want for singleplayer testing in [Project D2](https://www.projectdiablo2.com/).

### [Download](https://github.com/BetweenWalls/PD2-Singleplayer/archive/main.zip)

## Inclusions
* level 99 characters for each class with accurate stats and skill points (lower level characters in subfolders)
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

If you need to revert to an older version of PD2 (to drop maps or other incompatible items) you can use the patch_d2.mpq files included in the *Patches* folder. I've also made a character/stash conversion program that can update files to the most recent season: [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-character-converter-for-pd2)

If you also want to install Basemod, see this [reddit post](https://www.reddit.com/r/ProjectDiablo2/comments/otnk61/season_3_single_player_plugybasemod_item_pack/) by Swoosh. Switching to a different item pack is as easy as copying the desired *_LOD_SharedStashSave.sss* to your *Diablo II\Save* directory.

## Stash Organization
The shared stash has multiple pages and can be navigated in increments of 1, 10, or 100 pages at a time. The stash is organized as follows:

* (1-9) **Common Stuff**
* * empty page (for dumping items quickly or storing whatever's currently being tested)
* * workstation (runes, gems, uber materials, corrupting materials)
* * maps
* * crafting jewels, rejuvs, quest items, tokens, etc
* (10-19) **Unique Jewelry & Misc**
* * unique amulets/rings, charms, jewels
* * useful magic jewels
* * magic, rare, & crafted items
* (20-29) **Uniques - Class-Specific**
* (30-49) **Uniques - Armor**
* (50-79) **Uniques - Weapons**
* (80-89) **Sets**
* (90-109) **Runewords**
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

<!-- Notes
Some generated rare/crafted items have incorrect required levels
Some generated runeword item bases are missing certain stats, such as 10-50% FCR for staves
Some generated item bases may have incorrect armor values - they should be verified

Missing items:
* Non-Ethereal version of Wraith Flight
* Ormus' Robes with Combustion
* Ethereal versions of various skill-specific items such as Spirit Keeper, Ormus' Robes, and Spirit Ward
* Examples of popular low-level dueling (LLD) charms and other items
* Unique/Set items with variable inventory graphics - Rings, Amulets, Rainbow Facets, Gheed's Fortune
* Some useful item bases, especially elite ethereal weapons such as Legend Sword
* More examples of item bases with different pointmods, or Amazon weapons with +3 skills
* More examples of useful magic items such as +3 skill amulets, +6 Amazon javelins, +6 pointmod items, or even vanilla classics like JMoD

Item discrepancies (may just be game bugs):
* Laying of Hands has 250% Damage to Demons, range is 150-200
* Ribcracker doesn't have 30% faster cast rate like the S3 patch notes say it does
* Wraith Flight doesn't have the 50-150 magic damage that was mentioned in the S3 patch notes
* Demonhorn's Edge has 20% IAS rather than 30% as mentioned in the S3 patch notes
* Heavenly Garb only has +1 to Magic Skills instead of a range of 1-2 (from S2 patch notes)
* The Iron Jang Bong has 40-60% FCR instead of 30-50% as mentioned in the S3 patch notes
* Haemosu's Adamant only has +255 Defense vs. Melee instead of the max of 400 - not sure if that's actually the max, or if it just didn't generate with the max value
* Doom runeword only has a chance to cast level 18 Molten Boulder in non-staves, rather than level 28 in staves (difference wasn't mentioned in S3 patch notes)

-->
