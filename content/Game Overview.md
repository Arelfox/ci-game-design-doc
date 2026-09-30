---
tags:
---
# 1. Core Concept
- 1-4 player, cooperative pve first person extraction shooter
- Room clearing, resource management, and decision making under a timer
- Players raid fully autonomous, military/industrial facilities on different planets. These facilities are divided into procedurally connected rooms containing enemies and resources (see [Setting and Background](Story.md))
- [Resources](Materials.md) gathered by the player are carried out if they extract, but can also be used inside the run
	- raw materials and other resources are not brought into the run, only class gear is
- During a run, every few minutes [reinforcements](Enemies.md) (bosses) arrive **(finish)**
- **(finish) (i gotta decide what to put here and what to put in specifics bruh)**
## 1.1 Hook
- In depth damage system: [ballistic bullet penetration simulation](Combat.md) for enemies and players
- Procedurally generated room clearing runs
- Mostly grounded sci-fi setting and concepts
	- Enemy designs
- Anthropomorphic [class](Classes.md) identities with customizable skills and [weapons](Weapons.md)
	- customizable weapons with [attachments](Items.md), [ammo variations](Ammo.md), and an [in depth magazine system](Ammo.md)
- (finish)
## 1.2 How do players have fun?
- Class progression and content unlocking
- In-run powerscaling and character creative build crafting through ammo manufacturing, weapon attachments, and player gear
- Replayable roguelike runs
# 2. Design Doctrine
## Knowledge is Power
- More experienced players will perform better because they know more about the game, not because they have better gear
- Getting better comes down to learning [enemy](Enemies.md) armor layouts, [item](Items.md) functions, [printer](Crafting.md) recipes, [ammunition](Ammo.md) types, [room types](Facilities.md), good [class builds](Classes.md), and more
- Information about a room, or printer recipes, is intentionally left impartial. Players can spend resources to gather more information to decide if the room is worth clearing
## Realism
- Every added mechanic must have some grounded explanation
- realism = immersion = good worldbuilding (!= fun)
- Fun, cool, and interesting ideas will always come before however. Starting from or focusing on realism is boring
# 3. Abstracted Gameplay Loop
1. Choose desired facility/mission
2. Create entrance [class](Classes.md) loadout
3. Enter the [facility](Facilities.md) through an intro sequence with the [vehicle](Vehicle.md)
4. Clear following rooms, gathering supplies to improve gear and vehicle through [printers](Crafting.md)
5. Complete the objective before the difficulty escalates too much, [extract](Extraction.md) with the rewards
6. Spend earnings to unlock more content and make new builds
# 4. Resources
Resources in the game include:
- [Health](Health.md)
- [Ammo](Ammo.md)
- [Raw Materials](Materials.md)
- [Power](Power.md)
- Time
	- while not a physical resource, many actions such as [printing](Crafting.md), [healing](Health.md), scanning, [class](Classes.md) abilities, etc. all consume time
	- rooms become stronger and more [reinforcements](Enemies.md) arrive as time goes on
During the run, resources are used in [Crafting](Crafting.md) to create [items](Items.md), enhancing their combat capability
Outside of the run, resources can be used to hire (unlock) [characters](Classes.md), class skills, and class [weapons](Weapons.md)/gear
# 5. Game Comparison Chart (outdated rn)
does the game fill a niche? (for me personally)

| game                               | similarities                                                                                                                     | differences                                                                                                                                           |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| arc raiders                        | shield visual, loot gathering, future, mid ttk, extraction, robot enemies                                                        | has pvp, you can take weapons back to safe zone, 3rd person, map not procedurally generated, some outdoors, no class system (skills)                  |
| marathon                           | shield visual, loot gathering, fps, future, stylized (kinda cel shaded), mid ttk, class system, extraction                       | pvp only, you can take weapons back, map not procedurally generated, some outdoors                                                                    |
| ready or not                       | indoors + room based, fps, fast ttk, pve, around 1-4 players                                                                     | not future, no loot gathering, map not procedurally generated, no class system (free gear choice), slow paced and deliberate                          |
| risk of rain 2                     | loot gathering, basically same class system, around 1-4 players, dont take items back, future, pve                               | slow ttk, dumb enemy swarms, map not procedurally generated, some outdoors, 3rd person, roguelike elements are just multipliers of existing abilities |
| helldivers 2                       | faster ttk, around 1-4 players, pve, penetration and ballistic system, fps                                                       | dumb enemy swarms, outdoors, 3rd person, no loot gathering, no class system (free gear choice)                                                        |
| gtfo                               | around 1-4 players, pve, fast ttk, future, fps, extraction                                                                       | slow paced, stealth, different objective (check), no loot gathering of weapons                                                                        |
| deep rock galactic                 | indoors, around 1-4 players, class system, procedurally generated map, pve, future, fps, earn currency at end of run, extraction | dumb enemy swarms, not room based, slow ttk, terrain is your sandbox, no loot gathering of weapons                                                    |
| randomly generated droids (roblox) | future, room based procedurally generated map, around 1-4 players, class system, dont take items back                            | fps+3rd person, uses swords mostly, its made on slopblox, etc.                                                                                        |
| escape from tarkov                 | extraction, fast ttk, armor system, indoor areas, fps, has pve                                                                   | you can take weapons back, map not procedurally generated, no class system, has pvp                                                                   |
| lethal company                     | similar artstyle, procedurally generated map, idea of scavenging some industrial place, dont take items back, pve, future        | weapons, class system,                                                                                                                                |
| beta decay                         |                                                                                                                                  |                                                                                                                                                       |
| sulfur                             |                                                                                                                                  |                                                                                                                                                       |
