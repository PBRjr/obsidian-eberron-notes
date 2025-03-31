---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
aliases: ["Orc Terranova"]
---
# [Orc Terranova](Misc Files\CLI\compendium\bestiary\humanoid/orc-terranova-fleemortals.md)
*Source: Flee, Mortals! p. 211*  

```statblock
"name": "Orc Terranova (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Controller"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[breastplate](Misc%20Files/CLI/compendium/items/breastplate-xphb.md)"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "14"
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "9"
- !!int "16"
"speed": "35 ft."
"skillsaves":
  "Athletics": !!int "4"
"condition_immunities": "[prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 9"
"languages": "Common, Orc"
"cr": "2"
"traits":
- "desc": "When the terranova isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they are reduced to 0 hit points but not killed outright, they can make\
    \ an attack against an enemy (no action required) before the hit point reduction\
    \ is resolved. If the attack hits and its damage reduces the target to 0 hit points,\
    \ the terranova drops to 1 hit point instead of 0 hit points."
  "name": "Relentless (1/Turn)"
- "desc": "The terranova can sense anything a willing creature within 30 feet of them\
    \ can sense with tremorsense or Tremorspeak."
  "name": "Tremorspeak"
- "desc": "The terranova ignores difficult terrain."
  "name": "Unhindered"
"actions":
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft.,\
    \ one target touching the ground. Hit: 12 (2d8 + 3) bludgeoning damage, and\
    \ the target is knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Earth Pillar (1st-Level Spell)"
- "desc": "The terranova chooses up to five creatures on the ground within 15 feet\
    \ of them and stomps the ground. Each target must succeed on a DC 13 Strength\
    \ saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Quake"
- "desc": "The terranova chooses up to two creatures on the ground within 30 feet\
    \ of them. Each target must succeed on a DC 13 Strength saving throw or be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained).\
    \ A creature can use their action to free themself or another creature within\
    \ their reach, ending the effect on that creature."
  "name": "Sinkhole"
"bonus_actions":
- "desc": "The terranova takes the Dash action."
  "name": "Rush"
- "desc": "The terranova stomps, and 1d3 + 1 [mohler](Misc%20Files/CLI/compendium/bestiary/beast/mohler-fleemortals.md)s\
    \ pop out of the ground in unoccupied spaces within 30 feet of them. The mohlers\
    \ are friendly to the terranova and act immediately after the terranova's turn\
    \ on the same initiative count."
  "name": "Unearth Mohlers (1/Day)"
"source":
- "FleeMortals"
```
^statblock