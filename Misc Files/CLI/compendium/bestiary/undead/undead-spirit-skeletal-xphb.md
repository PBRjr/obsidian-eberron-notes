---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Undead Spirit (Skeletal)"]
---
# [Undead Spirit (Skeletal)](Misc Files\CLI\compendium\bestiary\undead/undead-spirit-skeletal-xphb.md)
*Source: Player's Handbook (2024) p. 328*  

```statblock
"name": "Undead Spirit (Skeletal) (XPHB)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac_class": "11 + the spell's level"
"stats":
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "4"
- !!int "10"
- !!int "9"
"speed": "30 ft."
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages you know"
"actions":
- "desc": "The spirit makes a number of attacks equal to half this spell's level (round\
    \ down)."
  "name": "Multiattack"
- "desc": "Ranged Attack Roll: YourSpellAttack Bonus equals your spell attack modifier,\
    \ range 150 ft. Hit: 2d4 + 3 + the spell's level Necrotic damage."
  "name": "Grave Bolt"
"source":
- "XPHB"
```
^statblock