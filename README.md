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
The singleplayer [PlugY mod](http://plugy.free.fr/) adds stash pages for all the items. A copy of PlugY 11.02 is included in the files, but any later version will work too.

1. Install Diablo II LoD
2. Install PD2
3. Add PlugY
* * copy PlugY.dll, PlugY.exe, and PlugY.ini to your *Diablo II\ProjectD2* directory, as well the Readme text file in your preferred language if you want to be able to reference it later (note that PlugY.ini has custom settings suited for PD2)
* * copy the PlugY folder to your *Diablo II* directory (it'll be *Diablo II\PlugY* will 11 files inside)
4. Add this collection
* * Copy the files from the included Save folder to your *Diablo II\Save* directory
5. Run PD2 as you would normally to get the latest patch/update
6. Run PlugY.exe as administrator

If you need to revert to an older version of PD2 (to drop maps or other incompatible items) you can use the patch_d2.mpq files included in the *Patches* folder. You can also update old files to the most recent season with [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2).

If you want to add Basemod or a newer version of PlugY, see this [reddit post](https://www.reddit.com/r/ProjectDiablo2/comments/otnk61/season_3_single_player_plugybasemod_item_pack/) by Swoosh. Switching to a different item pack is as easy as copying the desired *_LOD_SharedStashSave.sss* to your *Diablo II\Save* directory. Note that PlugY v11.02 doesn't spawn minions correctly in Uber Tristram and PlugY v14.03 doesn't handle some stash features correctly such as shared gold and indexing/navigation for personal stashes.

## Stash Organization
The shared stash has multiple pages and can be navigated in increments of 1, 10, or 100 pages at a time. The stash is organized as follows:

* (1-9) **Common Stuff**
* * empty page (for dumping items quickly or storing whatever's currently being tested)
* * workstation (runes, gems, uber materials, corrupting materials)
* * maps
* * rejuvs, quest items, tokens, etc
* (10-19) **Unique Jewelry & Misc**
* * unique amulets/rings, charms, jewels
* * useful magic jewels
* * magic, rare, & crafted items
* (20-29) **Uniques - Class-Specific**
* (30-49) **Uniques - Armor**
* (50-79) **Uniques - Weapons**
* (80-89) **Sets**
* (90-109) **Runewords**
* (110-129) **Charms**
* * resistance, damage, and mana charms
* * skillers for each class
* * various testing charms
* (130-139) **Base Items**
* (140-159) **Random Magic Items for Crafting**
* (160-189) **All Regular Items**

There are in-game commands for renaming stash pages and moving stash pages around - checkout the PlugY readme.

## Editing
The included blank characters can be edited with [Hero Editor](https://www.moddb.com/games/diablo-2-lod/downloads/hero-editor-v-104) or other editors, but only until they're loaded in-game. Once you play a character and save it, the character's file will be formatted differently. If you're making many edits, create copies of the unplayed character files before entering the game with them.

Note that while most statlines can be edited normally, some have been changed in PD2 and will prevent the character from loading properly.

<!-- Notes
Some generated rare/crafted items have incorrect required levels
Some generated runeword item bases are missing certain stats, such as 10-50% FCR for staves
Some generated item bases may have incorrect armor values - they should be verified

Missing items:
* Ethereal versions of certain skill-specific items (Spirit Keeper, Ormus' Robes, Spirit Ward)
* Examples of popular low-level dueling (LLD) charms and other items
* Unique/Set items with variable inventory graphics - Rings, Amulets, Rainbow Facets, Gheed's Fortune
* Some useful item bases, especially elite ethereal weapons such as Legend Sword
* More examples of item bases with different pointmods, or Amazon weapons with +3 skills
* More examples of useful magic items such as +3 skill amulets, +6 Amazon javelins, +6 pointmod items, or even vanilla classics like JMoD
-->
