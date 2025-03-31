---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
aliases: ["Orc Rampart"]
---
# [Orc Rampart](Misc Files\CLI\compendium\bestiary\humanoid/orc-rampart-fleemortals.md)
*Source: Flee, Mortals! p. 210*  

```statblock
"name": "Orc Rampart (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Soldier"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](Misc%20Files/CLI/compendium/items/chain-mail-xphb.md), [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "42"
"hit_dice": "5d8 + 20"
"stats":
- !!int "18"
- !!int "12"
- !!int "18"
- !!int "10"
- !!int "11"
- !!int "12"
"speed": "35 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Orc"
"cr": "2"
"traits":
- "desc": "When the rampart isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they are reduced to 0 hit points but not killed outright, they can make\
    \ an attack against an enemy (no action required) before the hit point reduction\
    \ is resolved. If the attack hits and its damage reduces the target to 0 hit points,\
    \ the rampart drops to 1 hit point instead of 0 hit points."
  "name": "Relentless (1/Turn)"
"actions":
- "desc": "The rampart makes two Spear attacks. If the rampart targets the same creature\
    \ with both attacks, the target has disadvantage on attack rolls against creatures\
    \ other than the rampart until the start of the rampart's next turn."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"reactions":
- "desc": "When an enemy within 5 feet of the rampart targets another creature with\
    \ an attack, the attacker must target the rampart instead."
  "name": "No!"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Orc%20Rampart.png"
```
^statblock