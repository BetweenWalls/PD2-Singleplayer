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
3. Add PlugY and this item/character pack by copying the *contents* of the **Diablo II** folder included here into your Diablo II directory
4. Run PD2 as you would normally to get the latest patch/update
5. Run PlugY.exe as administrator

When this collection is updated, getting the newest [shared stash](https://github.com/BetweenWalls/PD2-Singleplayer/blob/main/Diablo%20II/Save/_LOD_SharedStashSave.sss) only requires replacing the old version with the new one, although there may be other updated files that you may want as well. You can see which files were updated from the [commits page](https://github.com/BetweenWalls/PD2-Singleplayer/commits/main).

If you want to update old character/stash files, see [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2).

## Stash Organization
The shared stash has multiple pages and can be navigated in increments of 1, 10, or 100 pages at a time. The stash is organized as follows:

* (1-9) **Common Stuff**
  * empty landing page (for dumping items quickly or storing whatever's currently being tested)
  * workstation (runes, gems, uber materials, corrupting materials)
  * maps
  * rejuvs, quest items, miscellaneous items
* (10-19) **Unique Jewelry & Magic/Rare/Crafted Items**
  * unique amulets/rings, charms, jewels
  * useful magic jewels
  * magic, rare, & crafted items
* (20-29) **Uniques - Class-Specific**
* (30-49) **Uniques - Armor**
* (50-79) **Uniques - Weapons**
* (80-89) **Sets**
* (90-109) **Runewords**
* (110-129) **Charms**
  * resistance, damage, life, and mana charms
  * skillers for each class
  * various testing charms
* (130-139) **Popular Base Items**

Additionally, the **Bases** assassin character has a personal stash with ethereal and non-ethereal versions of all regular/magic items, so you can get exactly the desired item needed for crafting or runewords. They're separated from the shared stash to improve load times. 

* (1) **Empty Landing Page**
* (2-19) **Regular Armor**
* (20-49) **Regular Weapons**
* (50-69) **Magic Armor**
* (70-99) **Magic Weapons**

There are in-game commands for renaming stash pages and moving stash pages around, as well as some other useful commands such as renaming characters - checkout the PlugY Readme file.

## Editing
The included blank characters can be edited with [Hero Editor](https://www.moddb.com/games/diablo-2-lod/downloads/hero-editor-v-104) or other editors, but only until they're loaded in-game. Once you play a character and save it, the character's file will be formatted differently. If you're making many edits, create copies of the unplayed character files before entering the game with them. The [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2) may also be useful for converting certain files from PD2 to vanilla in order to edit them, although it was primarily designed for converting files in the opposite direction.

Note that while many attributes can be edited normally, the following have been changed in PD2 and will prevent vanilla characters from loading properly (unless converted first):

* Flat physical/elemental damage (reworked to deal splash damage)
* Enhanced damage (limit increased from 511%)

New affixes such as "Melee Attacks Deal Splash Damage" cannot be edited in this way at all without an advanced understanding of hex editing.

**Note:** Included characters are *not* currently Andariel-bugged. This can be changed by resetting the quest in Hero Editor and doing the bug in-game.

## Modification
If you would like to improve this collection with additional items, or just want to share feedback about how it could be improved, you can message me on reddit ([u/BetweenWalls](https://www.reddit.com/message/compose/?to=BetweenWalls)) or discord (@BetweenWalls#2390). You can also just open an [issue](https://github.com/BetweenWalls/PD2-Singleplayer/issues) here.

Potential Improvements:
* The Rathma-related items (Ancient Bone Fragments, Trang-Oul's Jawbone, Splinter of the Void, Voidstone, Tainted Worldstone Shard) will be added when the Rathma fight is enabled in singleplayer
* The uncommon Rathma rewards (The Third Eye, Band of Skulls, Cage of the Unsullied, unlimited TP/ID tomes) will be added when all 5 have been found from the live servers
* Ethereal versions of certain skill-specific items (Spirit Keeper, Ormus' Robes, Spirit Ward)
* Examples of popular low-level dueling (LLD) charms and other PvP-relevant items
* Unique/Set items with variable inventory graphics - Rings, Amulets, Rainbow Facets
* Regular ethereal armor with maximum defense values (they currently just have random values within the correct range)
* Regular superior weapons/armor with +15% ED
* More examples of regular item bases with different pointmods
* More examples of useful magic items such as +3 skill amulets, +6 Amazon javelins, +6 pointmod items, or even vanilla classics like JMoD
* More examples of rare/crafted items
* Testing charms with individual stats that have more granular values
* Testing charms with individual corruption effects
* Characters of each class pre-loaded with various build-relevant items in their personal stashes (1 page per build?) to help getting started with testing easier

<!-- Notes
Some generated rare/crafted items have incorrect required levels
Some generated runeword item bases are missing certain stats, such as 10-50% FCR for staves
Some generated item bases may have incorrect armor values - they should be verified
-->

**Note:** There is currently a bug with shared gold which prevents certain oskills (like those from Call to Arms) from working correctly - the skills work fine if there is no shared gold in the stash.