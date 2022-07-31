easy as in LoD mod by MAOMAC

to use this Single Player mod for Project Diablo 2 (currently made from season 5 patch 8)
make data/global/excel folders in ProjectD2 folder and copy all text files into excel folder
after that
add -direct -txt to shortcut
	(for example: change ...ProjectD2\PlugY.exe" to ...ProjectD2\PlugY.exe" -direct -txt)
	(if you still don't know how to do it use google and search for how to install simple diablo 2
	mods with -direct -txt method)

every change was made so that you can switch between this and normal PD2 safely
	(no stat/item changes/lvlup changes etc. that would brick your char/make it different from original PD2
	permamently so you can safely test it on your PD2 chars, and then remove it if you don't like it) 

I will try to explain what i think about my changes and reasons behind them etc.

TL:DR
	{
	- 'prime evil' stat removed from all monsters
	- monster HP reduced by 50% (so we technically "deal" 100% more damage compared to unmodded PD2)
	- monster and minion crit chance reduced from 5% to 0% (no crit)
	- you can leech from all monsters
	- battle cry duration buffed back from 5 seconds to 12 seconds
	- BO changed to: lvl 1 +350 hp , mana +175 / stat per lvlup same as PD2, 
	  (basically this lvl 1 BO = unmodded PD2 lvl 21, we got free 20 lvls)
	  (barb merc provides same bonus as in unmodded PD2-he uses new lvl 1)
	- lycanthropy changed to LoD values = +20% lvl 1 ,  +5%/lvlup
	- COMBAT REFLEXES: lvl 1 +500 hp and +50hp/lvl
	- NECRO corpse explosion %dmg buff x2 (from 5-10 to 10-20)
	- ASSASSIN death sentry corpse explosion %dmg buff x2 (from 3-5 to 6-10)
	- NECRO 'FAKE BUFF' TO REVIVE (I REMOVED 50% OF HP FROM BASE MONSTER STATS,
		AND THEN ADDED +100% HP BUFF {TO NEW BASE} WHEN REVIVING,
		SO NECRO REVIVES HAVE SAME HP AS IN UNMODDED PD2 - not visible
		in skill description but it's there)
	- MIRROR, ethVIAL, UNLIMITED KEY drop chance improved (ZOD rune rarity)
	- CORRUPTION chance rebalance-now every corruption has "equal" chance FROM a group
		(so if it rolls sockets for example you have 1/6 chance to have 6 sockets)
	- Monsters have X% Deadly Strike map corruption REMOVED
	- QOL:now you can cube multiple flawless gems into perfect gems
	}


Detailed explanation:


I made this small SP mod to Project Diablo 2 (Season 5 {currently Patch #8}) because i think balance in PD2 is ...not fun for me.
D2 for me (LoD and PoD) is the game where i can relax farming monsters and content doesn't require me
to be a mechanical GOD to kill a monster (Diablo Clone and RATHMA are WAY too hard for my old slow hands)

Also what is up with these items that have no real chance to drop? Unlimited key, mirror and ethVIAL?
it feels bad knowing there is this item that can do cool stuff but the chance to find it is like 1/infinity
I BUFFED DROPRATE of those items to ZOD runes. Still very rare but now they actually exist.
Corruption chances not evenly distributed is another thing i don't like. I prefer PoD system.

Dmg. If you compare dmg in PD2 and in LoD/PoD you will see that it was nerfed almost everywhere.
You deal from 2x as much to even 4x as much dmg in LoD/PoD.



so my changes:

'prime evil' stat removed from all monsters
	(minions and mercs are way to squishy vs bosses)

monster HP reduced by 50%
	(we deal way to little dmg compared to what we can do in LoD and/or PoD, even with this "2x damage" buff
	you still deal more in LoD/PoD {if you compare unmodded PD2 VS LoD/PoD it's usually 2x-3x and sometimes even 4x (lightning fury)}
	this also "nerfs" revives, BUT I COUNTER THAT with +100% HP buff to the skill (not visible in description, basically vs normal content
	revives are as tanky as in unmodded PD2, and vs bosses they are 4x as tanky because of prime evil stat being removed,
	revives are so squishy vs uber bosses in PD2 you can't even use them vs diablo clone, they just almost insta die, compare it to vanilla
	D2 where you could summon 20+ revives with GIGA HP buff LOL),
	also necro corpse explosion and assassin death sentry corpse explosion %damage is doubled (still GIGA nerfed compared to vanilla D2,
	for example corpse explosion from 70-120% to 10-20, sure you have corpses on demand with desecrate skill but to match the %dmg
	you have to cast it 6 times and	your curses and infinity don't lower resists like in LoD, AND the area is nerfed too),
	the only downside of 50% monster hp reduction is some monsters that we summon with reanimate in bows and stuff like that have reduced hp as well
	{unless it uses	stats from revive skill but i don't think so},
	this was the best and fastest method to buff our damage x2 for everything

monster and minion crit chance reduced from 5% to 0% (no crit)
	(Also removed that chance from our minions for consistency, they still deal WAY more dmg because of monster HP nerf)

you can leech from all monsters (ratio 100% in norm, 1/2 in NM, 1/3 in hell - so if you have 3%LL you leech 1% in hell)
	(crushing blow is basically "removed" {it stops working vs bosses when they are below 65% HP}
	attacks need to be rewarded SOMEHOW for the AR req,
	so i decided to make phys attack builds "leech tanks", i think it's a fair buff for crushing blow and life tap "removal" in PD2
	we have this in LoD anyway with draculs grasp we have constant leech on everything and +50LL, this is much weaker than that)


skills that give HP REBALANCED
	(LoD BO was removed and we lost WAY to much HP and mana,
	With these changes + life leech change you actually are rewarded a bit for attack rating requirement and being closer to danger.
	Also i think meele is supposed to be the mega tank, and with PD2 changes to HP bonuses meele feels not fun for me
	without this ranged feels like 100% safer)

	
skill changes:

	
	battle cry duration buffed from 5 seconds to 12 (still weaker duration than in season 4, it was 12 seconds +0.4 per lvl,
	with only 5 seconds there is no point for this to be on CTA for example, because if you want to use it with that item you have to
	switch->cast->swith and THEN do dmg for what.. 4 seconds? and then repeat? not fun)

	BO changed to: lvl 1 +350 hp , mana +175 (stat/lvl no change) (THIS IS STILL GIGA NERFED
	compared to VANILLA D2 where you get +95%+ to HP and MANA,)

	lycanthropy changed to LoD values (basically i change hp buff skills so we can almost
	reach hp levels of LoD, yes even with all the buffs here we still have less hp compared to LoD)	

	+20% lvl 1/ +5%/lvlup
	

	OAK SAGE - NO CHANGE - in LoD oak JUST DIES so often i consider it completely different skill so i leave it as is,
	also if i buffed it other spirits would be too weak in comparison

	COMBAT REFLEXES: (this is where i put a lot of old LoD BO for barbarian. i balanced BO+CR around 2kHP base,
	since barb usually has like 2k base,
	{i give more to CR because i had to balance this around barb merc so hes not op},
	you basically can reach almost LoD amount of HP if you max BO and CR but you have to spend 40 skillpoints so this is still a nerf compared to LoD)

	lvl 1 +500 hp and +50hp/lvl
	

	NECRO corpse explosion %dmg buff x2 (from 5-10 to 10-20)
		(buff to make the skill deal 2x damage with endgame gear {like other skills}
		because of reduced monster hp, also makes it better with low +skill,)

	NECRO 'FAKE BUFF' TO REVIVE (I REMOVED 50% OF HP FROM BASE MONSTER STATS, AND THEN ADDED +100% HP BUFF {TO NEW BASE} WHEN REVIVING,
		SO NECRO REVIVES HAVE SAME HP AS IN UNMODDED PD2)

	ASSASSIN death sentry corpse explosion %dmg buff x2 (from 3-5 to 6-10)
		(same reason as necro corpse explosion)

MIRROR, ethVIAL, UNLIMITED KEY drop chance improved
	(Added chance to find: -same as ZOD RUNE {FOR EVERY ZOD YOU FIND you will also find 1 mirror, vial and key on average}.
	Put in rune droptable so if a ZOD can't drop MIRROR/VIAL/KEY can't drop from this.
	Added ON TOP OF hardcoded chance, so you still can find a mirror in act 1 norm {gl with that lmao}
	Still very rare, but at least now they potentially EXIST, AND YOU CAN CRAFT WITH IT, not just a throphy because everything feels
	"not rare enough" to mirror/eth vial)

CORRUPTION chance rebalance-now every corruption has "equal" chance FROM a group, so if it rolls sockets for example you have 1/6 chance to have 6 sockets
	(So you don't have to find 100 shacos to have +3 shaco. still very hard to minmax items but at least not totally impossible for SSF)

Monsters have X% Deadly Strike map corruption REMOVED
	(monsters able to crit is too unpredictable for me to be fun, i want monster dmg to be consistent
	and not be surprised by a random crit. REMOVED)

QOL:now you can cube multiple flawless gems into perfect gems
	so we don't break our wrists, credit to BetweenWalls, i yoinked it from his CubeMain.txt , hope he doesn't mind i saved like 2hr of my time. ty ty


And that's it. Now the game is PLAYABLE for old noskill people like me

every change was made so that you can switch between this and normal PD2 safely (no stat/item changes/lvlup changes etc. that would brick your char/make it different from original PD2 permamently) 

reminder:
plugy is bugged in s5 because ofc it is
do not use shared gold, empty it (so you have 0 shared gold) and disable in plugy settings
	IT BUGS OUT MANY ITEMS, for example CTA
limit your stash (i do 501 personal and 2001 shared) and put something in the last page (personal and shared, i use a simple key), then save and exit.
	you do this to avoid a bug that randomly puts you into stash number QUADRILLION OR SOMETHING, very annoying.

UBER TRISTRAM IN PLUGY:
	first you need to kill ball in hell (have finished last quest) and i think you don't need to in online server. ( i can be wrong here
	but i remember there was a problem like that in the past).
	Spawn rates. they are GIGA broken compared to online. from my testing changing meph to 20, and dia/ball to 10 is comparable to online
	so i use:

[UBER QUEST]
ActiveUberQuest=1
UberMephistoX=25130
UberMephistoY=5143
UberDiabloX=25139
UberDiabloY=5139
UberBaalX=25139
UberBaalY=5135

ActiveUberMinions=1
UberMephistoSpawnPercent=20
UberMephistoSpawnRadius=30
UberBaalSpawnPercent=10
UberBaalSpawnRadius=30
UberDiabloSpawnPercent=10
UberDiabloSpawnRadius=30
ActiveUberDiabloRushTweekAI=1
ActiveUberBaalTeleportTweekAI=1
ActiveUberBaalChillingArmorTweekAI=0
UberBaalChillingArmorTimer=6000


some like 40/15/15 for example, standard settings of 80/30/30 make them spawn monsters like crazy

hf
	