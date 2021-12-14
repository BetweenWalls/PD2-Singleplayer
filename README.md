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
* all regular and magic equipment items
* some rare and crafted items

## Setup Guide
The singleplayer [PlugY mod](http://plugy.free.fr/) adds stash pages for all the items. A copy of PlugY v14.03 is included in the files.

1. Install Diablo II LoD
2. Install PD2
3. Add PlugY and this item/character pack by copying the contents of *Diablo II* to your Diablo II directory
4. Run PD2 as you would normally to get the latest patch/update
5. Run PlugY.exe as administrator

If you need to revert to an older version of PD2 (to drop maps or other incompatible items) you can use the patch_d2.mpq files included in the *Patches* folder. You can also update old files to the most recent season with [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2).

If you want to add Basemod or a newer version of PlugY, see this [reddit post](https://www.reddit.com/r/ProjectDiablo2/comments/otnk61/season_3_single_player_plugybasemod_item_pack/) by Swoosh. Switching to a different item pack is as easy as copying the desired *_LOD_SharedStashSave.sss* to your *Diablo II\Save* directory. Note that PlugY v11.02 doesn't spawn minions correctly in Uber Tristram and PlugY v14.03 doesn't handle some stash features correctly such as shared gold and indexing/navigation for personal stashes.

## Stash Organization
The shared stash has multiple pages and can be navigated in increments of 1, 10, or 100 pages at a time. The stash is organized as follows:

* (1-9) **Common Stuff**
* * empty landing page (for dumping items quickly or storing whatever's currently being tested)
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

Additionally, the **Bases** assassin character has a personal stash with ethereal and non-ethereal versions of all regular/magic items, so you can get exactly the desired item needed for crafting or runewords. They're separated from the shared stash to improve load times. 

* (1) **Empty Landing Page**
* (2-19) **Regular Armor**
* (20-49) **Regular Weapons**
* (50-69) **Magic Armor**
* (70-99) **Magic Weapons**

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
* Regular ethereal armor with maximum defense values (they just have random values within the correct range)
* More examples of item bases with different pointmods
* More examples of useful magic items such as +3 skill amulets, +6 Amazon javelins, +6 pointmod items, or even vanilla classics like JMoD
-->
