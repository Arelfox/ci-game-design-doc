---
tags:
---
# 1. Ammo
Aside from the amount you start with, ammunition can only be obtained via [printers](Crafting.md). More complex ammo is often rarer, and ammunition is caliber specific and must be loaded in a gun it is designed for.
## 1.1 Ammo Table
(abstracted)
(see [[Items]])

| name       | color       | function                                                       | cost/10 | rarity/10 |
| ---------- | ----------- | -------------------------------------------------------------- | ------- | --------- |
| ball (fmj) | white       | baseline                                                       | 1       | 1         |
| jhp        | brown       | less penetration, more damage, human damage bonus              | 2       | 2         |
| ap         | green       | more penetration                                               | 3       | 2         |
| api        | orange      | more penetration, does DoT for ammo, core, and battery modules | 4       | 2         |
| aphe       | red         | penetration, explodes after                                    | 6       | 4         |
| aphc       | dark green? | even more penetration                                          | 6       | 5         |
| apds       | purple      | even even more penetration                                     | 8       | 7         |
| duplex     | light blue  | 2 bullets per shot, more damage total, slightly less pen       | 6       | 6         |
| smart      | blue        | automatically homes towards weakspots                          | 10      | 8         |
| he         | yellow      | destroy external modules                                       | 3       | 3         |
| airburst   | pink        | explosive damage behind cover                                  | 9       | 9         |

### Shotguns:

| name            | color  | function                                 | cost | rarity |
| --------------- | ------ | ---------------------------------------- | ---- | ------ |
| #1 buckshot     | white  | baseline shotgun            0 buckshot   |      |        |
| #0000 buckshot  | green  | way less pellets for way more damage     |      |        |
| flechette       | orange | more penetration                         |      |        |
| slug            | blue   | single shot, more penetration and damage | 4    |        |
| slug (apds)     | purple | single shot, even more penetration       | 9    |        |
| slug (he)       | yellow | destroy external modules                 |      |        |
| slug (airburst) | pink   | explosive damage behind cover            | 10   |        |
| xrep (?)        |        | stuns?                                   |      |        |

## 1.2 Ammo Calibers
- 5.56×45 (light)
	- no apds/airburst option
	- less explosive aphe, he
- 6.8×51 (medium)
- 7.62×51 (older medium)
- 8.6×60 (heavy)
- 12.7×99 (anti material)
- 8.5x60 ET (electrothermal cartridge)
- 9x19 (light pistol)
	- no apds/airbust option
- 10x25 (medium pistol)
	- no apds/airburst option
- 12.7x33 (heavy pistol)
- 10 gauge (medium shotgun)
- 12 gauge (light shotgun)
# 2. Gun Magazines
- Mags must be loaded in the [inventory](Inventory.md). Reloading does not magically pull from your ammo supply automatically
- Mags are represented by a general white outline filled with colors representing the proportion of ammo
	- on hover or in the mag select wheel you will still see text describing the contents (such as AP or AP/JHP) under
	- unloaded ammo will also have their respective colors to allow for association during gameplay
- The amount left in your inventory compatible with the equipped gun will appear on the ui, along with its coloring
## 2.1 Reloading
- tap r
	- reloads and picks the most full (tiebroken by rightmost in inventory for fine tuning) mag
- double tap r
	- same thing but drops the mag on ground for a quicker reload (can be picked up ofc)
- hold r
	- opens ui wheel to select which mag to load