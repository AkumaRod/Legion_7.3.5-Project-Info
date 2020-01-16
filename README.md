# Legion 7.3.5 Project
Private Source MMO Framework (master = 7.3.5.26972)

## Status Checker and Informations

* [Introduction](#introduction)
* [Starting Zones](#starting-zones)
* [Zones](#zones)
* [Classes](#classes)
* [Systems and Core functions](#systems-and-core-functions)
* [Professions](#professions)
* [World Events](#world-events)
* [Discord](#discord)

--------------

## Introduction

This Legion 7.3.5 Project is a *MMORPG* Framework based mostly in C++. The project doesn't have a final name yet, it might change in the future.

This core had never been deployed on a live server, so the audience had no chance to try it. Those who have accessed it so far were members of my old retail guild (Pussycat Growls) and could only try it out during a CBT (Closed Beta Test). It is important to note that the version tested under CBT is much older than the current version. The status that is described is from July 19th 2018 (the last documentation), so I'll try to keep it up to date (as my time allows it to be up to date - I working in this project, and the current statement need to be re-checked for the live status update).

I have been working on this server core and db for almost 9 years now (with daily 8-12 hours basis), which was started with a TBC expansion. Since then I have been constantly improving this core's code. I've been tremendous in the TBC expansion and can say today that I've managed to put together a relatively stable and playable Legion 7.3.5 core, which I hope will appeal to the players on the Live server.

It is fully based on *TrinityCore*, with a lot of Upgrades and Features.
Check the list below to get a "mostly-full" picture about what can this future server offer for its players, such as:
- Classes,
- Dungeons,
- Raids,
- Systems and other aspects of my World of Warcraft - Legion 7.3.5 project.

--------------

## Starting Zones

**** Horde ****

- Eversong Woods (Blood Elf @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)
- Durotar (Orc @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)
- Echo Isles (Troll @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)
- Kezan (Goblin @ Racials: Working ✔ 100%) - Working (Overall scripts 78%)  
- Mulgore (Tauren @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)   
- Trisfal Glades (Undead @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)

**** Alliance ****

- Elwynn Forest (Human @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)  
- Gilneas (Worgen @ Racials: Working ✔ 100%) - Working (Overall scripts 93%)
- Teldrassil (Night Elf @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)
- Dun Morogh (Dwarf @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)
- Dun Morogh (Gnome @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)
- Azuremyst Isle & Bloodmyst Isle (Draenei @ Racials: Working ✔ 100%) - Working (Overall scripts 100%)

**** Neutral ****

- The Wandering Isle (Pandaren @ Racials: Working ✔ 100%) - Working (Overall scripts 91%)
- Mardum (Demon Hunter @ Racials: Working ✔ 100%) - Working (Overall scripts 99%)

**** Allied Races ****

- Telogrus Rift (Void Elf @ Racials: Not Working properly) - Working (Overall scripts 67%)
- Highmountain (Highmountain Tauren @ Racials: Not Working properly) - Working (Overall scripts 22%)
- Suramar (Nightborn @ Racials: Not Working properly) - Working (Overall scripts 46%)
- The Vindicaar (Lightforged Draenei @ Racials: Not Working properly) - Working (Overall scripts 50%)

--------------

## Zones

(Zone contents below Legion, are tested by dedicated testers, members from my old retail guild named: "Pussycat Growls". Last CBT test was started at 2018 April 22nd, and ended at 2018 December 20th.)

**** Eastern Kingdoms **** (under heavy development)
- Playable and working, but still there are a lot of bugs and phasing errors.

**** Great Sea ****
- Kezan - Working 
- Lost Isles - Working 
- The Maelstrom - Working 
- Wandering Isle - Working

**** Kalimdor **** (under heavy development)
- Playable and working, but still there are a lot of bugs and phasing errors.

**** Outland ****
- Blade's Edge Mountains - Working
- Hellfire Peninsula - Working 
- Nagrand - Working 
- Netherstorm - Working
- Shadowmoon Valley - Working 
- Terokkar Forest - Working 
- Zangarmarsh - Working 

**** Northrend ****
- Borean Tundra - Working 
- Crystalsong Forest - Working   
- Dragonblight - Working
- Grizzly Hills - Working
- Howling Fjord - Working
- Hrothgar's Landing - Working
- Icecrown - Working 
- Wintergrasp - Working
- Sholazar Basin - Working 
- Storm Peaks - Working
- Zul'Drak - Working

**** Mists of Pandaria Pandaria ****
- Dread Wastes - Working 
- Isle of Giants - Working
- Isle of Thunder - Working
- The Jade Forest - Working
- Kun-Lai Summit - Working
- Krasarang Wilds - Working
- Timeless Isle - Working
- Townlong Steppes - Working 
- Vale of Eternal Blossoms - Working
- Valley of the Four Winds - Working  
- Veiled Stair - Working

**** Warlords of Draenor (Draenor) ****
- Frostfire Ridge - Working
- Shadowmoon Valley - Working
- Gorgrond - Working
- Talador - Working
- Spires of Arak - Working
- Nagrand - Working
- Tanaan Jungle - Working
- Ashran - Not Working

**** Legion Broken Isles ****
(Never tested by CBT players. OBT test coming 2020's March)

- Azsuna - Mostly complete and working, but not finished yet (about 60% complete)
- The Broken Shore - Mostly complete and working, but not finished yet (about 50% complete)  
- Eye of Azshara - Mostly complete and working, but not finished yet (about 45% complete)  
- Highmountain - Mostly complete and working, but not finished yet (about 68% complete)  
- Stormheim - Mostly complete and working, but not finished yet (about 31% complete)  
- Helheim - Mostly complete and working, but not finished yet (about 20% complete)  
- Suramar - Mostly complete and working, but not finished yet (about 59% complete)  
- Val'sharah - Mostly complete and working, but not finished yet (about 87% complete)  


Additional note:
The tests was made on a Linux based dedicated server. There was 172 Testers during the last CBT phase. I hope the next one will gather much more attention. :)

--------------

## Classes

- Death Knight - Spells are Working ✔  at: ~90% (only 2-3 spells, and a few % of the talents are not Working properly right now)
- Demon Hunter - Spells are Working ✔  at: ~88% (only 3-4 spells, and a few % of the talents are not Working properly right now)
- Druid - Spells are Working ✔  at: ~89% (only 3-4 spells, and a few % of the talents are not Working properly right now)
- Hunter - Spells are Working ✔  at: ~76% (only 5-6 spells, and a few % of the talents are not Working properly right now)
- Mage - Spells are Working ✔  at: ~90% (only 2-3 spells, and a few % of the talents are not Working properly right now)
- Monk - Spells are Working ✔  at: ~70% (only 4-5 spells, and a few % of the talents are not Working properly right now)
- Paladin - Spells are Working ✔  at: ~87% (only 3-4 spells, and a few % of the talents are not Working properly right now)
- Priest - Spells are Working ✔  at: ~91% (only 2-3 spells, and a few % of the talents are not Working properly right now)
- Rogue - Spells are Working ✔  at: ~94% (only 1-2 spells, and a few % of the talents are not Working properly right now)
- Shaman - Spells are Working ✔  at: ~84% (only 3-4 spells, and a few % of the talents are not Working properly right now)
- Warlock - Spells are Working ✔  at: ~92% (only 2-3 spells, and a few % of the talents are not Working properly right now)
- Warrior - Spells are Working ✔  at: ~96% (only 1-2 spells, and a few % of the talents are not Working properly right now)

Please note:
Those % are just estimated valus. The numbers comes from: Spells+Talents combinations (Passive and Actives overall).

--------------

## Dungeons and Raids

Classic, The Burning Crusade, Wrath of the Lich King and Cataclysm

- Working Classic dungeons: (All Dungeons are Scripted)
- Working Classic Raids: (All Raids are Scripted on All modes)
- Working TBC dungeons:  (All Dungeons are Scripted)
- Working TBC Raids: (All Raids are scripted)
- Working WoTLK dungeons:  (All Dungeons are Scripted on All modes)
- Working WoTLK  Raids: (All Raids are Scripted on All modes)
- Working dungeons: (All Dungeons are Scripted on All modes)

Working MoP dungeons: (All Dungeons are Scripted on All modes)
- Gate Setting Sun
- Mogushan Palace
- Shadopan Monastery
- Siege Niuzao Temple
- Stormstout Brewery
- Temple Jade Serpent

Working MoP Raids: (All Raids are Scripted on All modes)
- Heart Of Fear (Need additional fixes trough DataBase - DMG/Armor/Auras)
- Mogushan Vault (Need additional fixes trough DataBase - DMG/Armor/Auras)

Working MOP World Bosses: (All WBs are Scripted)
-  Oondasta
-  Galion
-  Sha of Anger

Working WoD dungeons: (All Dungeons are Scripted on All modes)
- Bloodmaul Slag Mines 
- Everbloom
- Shadowmoon Burial Grounds

Working WoD Raids: (All Raids are Scripted on All modes)
- Highmaul

Working Legion dungeons: (All Dungeons are Scripted on All modes)

Legion World Bosses (Scripted)
- Nithogg
- Humongris
Legion Raids: (Under heavy development)
- Emerald Nightmire: (Normal, Heroic, Mythic) (1/8)
- Trial of Valor: (Not started yet)
- The Nighthold: (Not started yet)
- Tomb of Sargeras: (Not started yet)
- Antorus, The Burning Throne (Not started yet)
 
--------------

## Systems and Core functions

- Advanced pathfinding: Working, but some times its fails
- AoE loot: Working ✔  (100%)
- Level-Sync: Working ✔  (100%)
- Achievements: Working, but need some fixes
- Account-wide collections (Mounts, Heirlooms, Pets, Outfits/Cosmetics): Working
- Transmogrifier: Working ✔  (100%)
- Void Storage: Working ✔  (100%)
- Base & Bonus stats: Working ✔  (100%)
- Battle-Pet system: Working ✔  (open-wprld and player duels aswell, but the queue mechanic need to be reworked)
- Brawler: Working, but need some fixes for the queue pop (instantly pops and not find opponent)
- Garrisons: Working ✔  (Build, Upgrade and Mission Board)
- Shipyards: Working ✔  (Build, Ship craft and upgrade, Mission Board)
- Followers: Working, but not 100%
- Class Halls: Fully spawned, Mission board functional, but some phasing issues are there
- Artifact Weapons: Working ✔  (Skins, Traits and Spells)
- Artifact Weapon Quest lines: Fully working
- Artifact Weapon (Challenger mode and skind) - Not working yet
- Timewalker Dungeons: Working ✔  (100%)

--------------

## Professions

- Alchemy: Working
- Blacksmithing: Working
- Inscription: Working
- Jewelcrafting: Working
- Mining: Working (but not provide XP yet)
- Tailoring: Working
- Engineering: Working
- Herbalism: Working (but not provide XP yet)
- Enchanting: Working
- Leatherworking: Working
- Skinning: Working
- Archaeology: Working

--------------

## World Events

Holidays
- Brewfest: (creatures and objects are missing)
- Children's Week: (creatures and objects are missing)
- Day of the Dead: Working
- Feast of Winter Veil: Working
- Fireworks Spectacular	(creatures and objects are missing)
- Hallow's End: Working
- Harvest Festival: Not working at all
- Love is in the Air: Not working at all
- Lunar Festival: Not working at all
- Midsummer Fire Festival: Working
- Noblegarden: Working
- Pilgrim's Bounty: Quests are complete, but creatures and objects are missing
- Pirates' Day: Working

Recurring
- Arena Skirmish Bonus Event - Not Working
- Battleground Bonus Event - Not Working
- Cataclysm Timewalking Dungeon Event - Working
- Darkmoon Faire - Not Working
- Kirin Tor Tavern Crawl - Working
- Legion Dungeon Event - Working
- Northrend Timewalking Dungeon Event - Working
- Outland Timewalking Dungeon Event - Working
- Pet Battle Bonus Event - Working
- Stranglethorn Fishing Extravaganza - Working
- World Quest Bonus Event - Working

## Discord

If you intrested, you can join to this Discord server, where you can get more informations about the Betas and the Launch date.
Above that, you can ask from me about the project there and you can request in-game made screenshots and videos about anything which is related for our future open (and/or the server state).

Discord invite link: https://discord.gg/Ncx3pzN
