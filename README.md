# PD2-Singleplayer
This collection aims to include everything you'd want for singleplayer testing in [Project D2](https://www.projectdiablo2.com/).

If you're just looking for PlugY without the item pack, characters, or modpacks, see [PD2-PlugY](https://github.com/BetweenWalls/PD2-PlugY#pd2-plugy).

### [Download](https://github.com/BetweenWalls/PD2-Singleplayer/archive/main.zip)

## Setup Guide
The singleplayer [PlugY mod](http://plugy.free.fr/) adds stash pages for all the items, fixes ubers, and allows unlimited skill/stat resets as well as several other optional features. A copy of PlugY v14.03 is included in the files.

1. Pre-Setup - Ensure you have *Diablo&nbsp;II&nbsp;LoD* and *PD2* installed; if you already use PlugY, backup your shared stash file
2. Add PlugY and this item/character pack - copy **ProjectD2** and **Save** from the included **Diablo&nbsp;II** folder into your own **Diablo&nbsp;II** folder
    * The items and characters are in the **Save** folder so if you don't want them, don't copy them
    * The characters are in subfolders within the **Save** folder - copy whichever you want into the main **Save** folder to access them in-game
    * PlugY features can be enabled/disabled within the **PlugY.ini** file
3. Run **PlugY.exe** as administrator

When new seasons/patches are released, you'll need to run PD2 via the launcher to update the game. Running the game via the launcher will also update your lootfilter.

The **PlugY.exe&nbsp;(modded)** file is a shortcut for using [modpacks](https://github.com/BetweenWalls/PD2-Singleplayer/tree/main#modpacks) and is preconfigured to use the default English installation directory. If your **Diablo&nbsp;II** directory is *not* **C:\Program&nbsp;Files&nbsp;(x86)\Diablo&nbsp;II** then it won't function until you modify its "Target" and "Start&nbsp;in" properties.

### Troubleshooting
Setup:
* PlugY may not load correctly if it is added after a fresh PD2 installation or if PD2 hasn't been updated in a while - run the game once via the launcher to fix it
* Older versions of PlugY had a different folder structure (some files were in the **Diablo&nbsp;II** folder instead of the **Diablo&nbsp;II/ProjectD2** folder) so they won't be ovewritten automatically - delete those old files manually if there are any issues
* Old characters from previous seasons may not load correctly - to update them, see [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2)

PlugY bugs:
* If a single stash page contains many items that each have many affixes (e.g. maps) then crashes can occur when accessing that page or at any time if that page was the most recently viewed page
    * FIX: Reduce the number of maps stored per page, or switch to another page before leaving the stash
* Having gold in the shared stash can cause issues such as preventing oskills from working correctly (disabled by default)
    * FIX: Ensure no "shared gold" remains in the stash during normal gameplay
* The "toggle stash" button may be set to the wrong stash upon loading until interacting with the current stash - this happens if the most recent stash interaction prior to saving/exiting involved using a PlugY stash button instead of manipulating an item in the stash
    * FIX: Add or remove an item from the stash prior to saving/exiting (this also fixes the button at any time if it's set wrong)
* Stash navigation may be buggy if the stash pages are empty - the navigation will appear to jump between the wrong pages, but it is actually just displaying the wrong page numbers for all pages between the first page (page&nbsp;1) and the first index (page&nbsp;10)
    * FIX: Put an item on page 10 or higher and save/exit

## Stash Organization
The shared stash has multiple pages and can be navigated in increments of 1, 10, or 100 pages at a time. The stash is organized as follows:

* (1-9) **Common Stuff**
  * empty landing page (for dumping items quickly or storing whatever's currently being tested)
  * workstation (runes, gems, uber materials, corrupting materials)
  * maps, rejuvs, quest items, miscellaneous items
* (10-19) **Magic/Rare/Crafted Items**
  * jewels, amulets, rings, quivers, etc
* (20-29) **Recipe References**
  * upgrading, socketing, & repairing rune/gem combos
  * edited items that show guaranteed affixes for each crafting recipe, crafting rune/gem combos
* (30-39) **Uniques/Sets - Jewelry & Class-Specific Items**
  * amulets/rings, charms, jewels
  * amazon weapons, claws, orbs, etc
* (30-49) **Uniques/Sets - Armor**
* (50-79) **Uniques/Sets - Weapons**
* (90-98) **Sets** (grouped together)
* (99) **Exclusive DClone/Rathma Items**
* (100-119) **Runewords**
* (120-139) **Charms**
  * resistance, damage, life, and mana charms
  * skillers for each class
  * various testing charms
* (140-149) **Popular Base Items**

Additionally, the **Bases** assassin character has a personal stash with ethereal and non-ethereal versions of all regular/magic items, so you can get exactly the desired item needed for crafting or runewords. They're separated from the shared stash to improve load times. 

* (1) **Empty Landing Page**
* (2-19) **Regular Armor**
* (20-49) **Regular Weapons**
* (50-69) **Superior Armor**
* (70-99) **Superior Weapons**
* (100-119) **Magic Armor**
* (120-149) **Magic Weapons**

Items can be duplicated by making a file backup of the shared stash and transfering items from the stash to a character before restoring the stash file, or vice versa. Files can also be set as "read only" to eliminate the need to backup and restore them for each transfer. The fastest way to duplicate items is to use the "testing" [modpack](https://github.com/BetweenWalls/PD2-Singleplayer/tree/main#modpacks).

There are in-game commands for renaming stash pages and moving stash pages around, as well as some other useful commands - checkout the PlugY [Readme](https://raw.githubusercontent.com/BetweenWalls/PD2-Singleplayer/main/Diablo%20II/ProjectD2/PlugY_The_Survival_Kit_-_Readme.txt) file.

## Characters
This collection includes blank characters of each class at levels 30, 70, 90, and 99. These characters can be edited with vanilla editors prior to being loaded in-game.

Several "showcase" characters are also included for each class. These characters are from previous ladders that were shared with the community and showcased on stream.

Included characters are *not* currently Andariel-quest-bugged, which is something that can only occur in singleplayer. To quest-bug a blank character, reset their Andariel quest in Hero Editor and do the bug in-game.

Characters can be renamed by using the ***/renamechar&nbsp;newname*** command. Checkout the PlugY [Readme](https://raw.githubusercontent.com/BetweenWalls/PD2-Singleplayer/main/Diablo%20II/ProjectD2/PlugY_The_Survival_Kit_-_Readme.txt) file for other useful commands.

## Editing
The included blank characters can be edited with [Hero Editor](https://www.moddb.com/games/diablo-2-lod/downloads/hero-editor-v-104) or other editors, but only until they're loaded in-game. Once you play a character and save it, the character's file will be formatted differently. If you're making many edits, create copies of the unplayed character files before entering the game with them. The [PD2-Converter](https://github.com/BetweenWalls/PD2-Converter#simple-characterstash-converter-for-pd2) may also be useful for converting certain files from PD2 to vanilla in order to edit them, although it was primarily designed for converting files in the opposite direction.

Note that while many attributes can be edited normally, the following have been changed in PD2 and will prevent vanilla characters from loading properly (unless converted first):

* Flat physical/elemental damage (reworked to deal splash damage)
* Enhanced damage (limit increased from 511%)

New affixes such as "Melee Attacks Deal Splash Damage" cannot be edited in this way at all without an advanced understanding of hex editing.

## Modification
If the items in this collection are insufficient, you may want to look into [text modding](https://d2mods.info/forum/viewtopic.php?f=4&t=34455). By modifying the game's text files, you can spawn items via custom cube recipes, adjust the ranges for affixes that can appear on items, and much more. Here are the basic steps:

1. Extract the game's text files from **pd2data.mpq** (found in **Diablo&nbsp;II/ProjectD2**) using an [MPQ editor and D2 listfile](http://www.zezula.net/en/mpq/download.html) - the text files will be in **/data/global/excel**
2. Edit whichever files you want (for example, **CubeMain.txt** includes the cube recipes)
    * This is best done in a spreadsheet program since the files have tab-separated data
3. Copy the edited files to your game directory inside a new folder structure: **Diablo&nbsp;II/ProjectD2/data/global/excel**
4. Create (and run) a new shortcut for **PlugY.exe** with additional commands in the target field so that the game uses your edited text files: -direct -txt

These steps have already been done for this collection - the game's text files are in **Diablo&nbsp;II\ProjectD2\data\global\excel\modpacks** along with modified text files from the "testing" modpack in the above folder.

## Modpacks
[Modpacks](https://github.com/BetweenWalls/PD2-Singleplayer/tree/main/Diablo%20II/ProjectD2/data/global/excel/modpacks) are custom game modifications. They can alter the game in a variety of ways and have different purposes, such as streamlining testing or improving normal gameplay. Some modpacks may be minimalist (only adding minor quality-of-life features and fixing bugs) while others may be major overhauls with significant balance changes or new features.

The ["testing"](https://github.com/BetweenWalls/PD2-Singleplayer/tree/main/Diablo%20II/ProjectD2/data/global/excel/modpacks/testing) modpack is setup by default to help with acquiring specific items for more thorough testing. It is not designed for normal gameplay - when used alongside the item pack, it trivializes item acquisition. If your Diablo II installation is in **C:\Program&nbsp;Files&nbsp;(x86)** (the default location) you'll only need to launch the **PlugY.exe&nbsp;(modded)** shortcut to get access to several useful cube recipes from the "testing" modpack:
* reroll any non-crafted item with Horadrim Orb
* duplicate most items with Key, duplicate jewels with Jewel Fragments
* use crafted items as ingredients for crafting recipes
* generate set/unique items of a given base with Rancid (green) or Oil (gold) Potions
* upgrade regular/magic item bases with Zakarum Orb
* make items ethereal with Cartographer's Orb
* upgrade regular item quality with Arcane Orb, and downgrade with Orb of Destruction
* safely remove socketed gems/runes/jewels with Hel Rune
* set the number of sockets with runes #1-6 based on the number of the rune used
* roll specific corruption modifiers with Angelic Orb and a rune: runes #1-10 are for low-tier mods, runes #11-20 are for mid-tier mods, and runes #21-30 are for high-tier mods

After getting whatever items you want via the "testing" modpack or other modifications, simply run the original **PlugY.exe** file to make the game run normally. The original game files aren't changed so you can experiment with text mods like this without fear of messing something up.

If you've made your own PD2 modpack and would like it to be available here, I'd be glad to add it.

## Feedback
If you would like to improve this collection with additional items, or just want to share feedback about how it could be improved, you can message me on reddit ([u/BetweenWalls](https://www.reddit.com/message/compose/?to=BetweenWalls)) or discord (@BetweenWalls). You can also just open an [issue](https://github.com/BetweenWalls/PD2-Singleplayer/issues) here.

Potential Improvements:
* Testing charms with individual corruption stats or other stats with more granular values
* More examples of regular item bases with different +3 pointmods
* More examples of useful magic items like +3 skill tree & +3 pointmod items or vanilla classics like JMoD
* More examples of rare/crafted items
* Examples of popular low-level dueling (LLD) charms and other PvP-relevant items
* More "showcase" characters

<!-- Notes
Low Priority Improvements
* Ethereal versions of certain skill-specific items (Spirit Keeper, Ormus' Robes, Spirit Ward)
* Some generated rare/crafted items have incorrect required levels
* Some generated runeword item bases are missing certain stats, such as 10-50% FCR for staves
* Some example runewords are made with items that have higher level requirements than the runewords themselves
-->
