---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/ambusher
statblock: inline
aliases: ["Bog Body"]
---
# [Bog Body](Misc Files\CLI\compendium\bestiary\undead/bog-body-fleemortals.md)
*Source: Flee, Mortals! p. 334*  

```statblock
"name": "Bog Body (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Ambusher"
"alignment": "typically  Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"stats":
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "5"
- !!int "10"
- !!int "6"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "2"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., passive Perception 12"
"languages": "understands the languages they knew in life but can't speak"
"cr": "1"
"traits":
- "desc": "A creature who deals piercing or slashing damage to the bog body while\
    \ within 5 feet of them takes 3 (1d6) acid damage."
  "name": "Acidic Blood"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage. If the target is a Medium or smaller creature, they\
    \ are [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) (escape DC 13).\
    \ Until this grapple ends, the bog body can't make a Slam attack against another\
    \ target."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30 ft., one target. Hit: 5\
    \ (1d4 + 3) bludgeoning damage plus 3 (1d6) acid damage."
  "name": "Sling Mud"
- "desc": "If the bog body is in swampy terrain, they can submerge themself beneath\
    \ the water and mud. While submerged, the bog body is heavily obscured.\n\nIf\
    \ the bog body is grappling a target when they submerge, the target submerges\
    \ with them. While submerged, the target is heavily obscured, [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained),\
    \ and unable to breathe, and takes 4 (1d8) acid damage at the start of each\
    \ of their turns.\n\nA bog body can resurface as a bonus action. When they do\
    \ so, a target they have [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ also resurfaces."
  "name": "Submerge"
"source":
- "FleeMortals"
```
^statblock