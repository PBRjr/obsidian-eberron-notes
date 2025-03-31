---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
aliases: ["Orc Bloodrunner"]
---
# [Orc Bloodrunner](Misc Files\CLI\compendium\bestiary\humanoid/orc-bloodrunner-fleemortals.md)
*Source: Flee, Mortals! p. 206*  

```statblock
"name": "Orc Bloodrunner (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[spiked shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"stats":
- !!int "14"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "9"
- !!int "10"
"speed": "60 ft."
"saves":
  "Dexterity": !!int "5"
"skillsaves":
  "Athletics": !!int "4"
  "Acrobatics": !!int "5"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
- "desc": "When the bloodrunner isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they are reduced to 0 hit points but not killed outright, they can make\
    \ an attack against an enemy (no action required) before the hit point reduction\
    \ is resolved. If the attack hits and its damage reduces the target to 0 hit points,\
    \ the bloodrunner drops to 1 hit point instead of 0 hit points."
  "name": "Relentless (1/Turn)"
- "desc": "The bloodrunner can occupy a [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ creature's space. The first time the bloodrunner enters a [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ creature's space on the bloodrunner's turn, the [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ creature takes 3 (1d6) bludgeoning damage. When a [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ creature in the bloodrunner's space stands up, the creature enters the nearest\
    \ unoccupied space of their choice."
  "name": "Unimpeded"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage. If the bloodrunner moves at least 10 feet before hitting\
    \ a Large or smaller creature with this attack, the bloodrunner can choose to\
    \ knock the target [prone](Misc%20Files/CLI/rules/conditions.md#Prone) or push\
    \ them up to 10 feet away."
  "name": "Spiked Shield"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage."
  "name": "Javelin"
"reactions":
- "desc": "When the bloodrunner makes a Dexterity saving throw, they can gain advantage\
    \ on the save. To do so, the bloodrunner can't be [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
    \ [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled), or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)."
  "name": "Juke"
"source":
- "FleeMortals"
```
^statblock