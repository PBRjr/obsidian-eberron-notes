---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
aliases: ["Orc Godcaller"]
---
# [Orc Godcaller](Misc Files\CLI\compendium\bestiary\humanoid/orc-godcaller-fleemortals.md)
*Source: Flee, Mortals! p. 209*  

```statblock
"name": "Orc Godcaller (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Support"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"stats":
- !!int "14"
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "13"
- !!int "19"
"speed": "35 ft."
"saves":
  "Wisdom": !!int "3"
"skillsaves":
  "Insight": !!int "3"
  "Performance": !!int "8"
  "Arcana": !!int "3"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Orc"
"cr": "4"
"traits":
- "desc": "When the godcaller isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they are reduced to 0 hit points but not killed outright, they can make\
    \ an attack against an enemy (no action required) before the hit point reduction\
    \ is resolved. If the attack hits and its damage reduces the target to 0 hit points,\
    \ the godcaller drops to 1 hit point instead of 0 hit points."
  "name": "Relentless (1/Turn)"
"actions":
- "desc": "Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 30 ft.,\
    \ one creature who can hear the godcaller. Hit: 18 (4d6 + 4) thunder damage."
  "name": "Power Chord (1st-Level Spell)"
- "desc": "The godcaller chooses another creature within 30 feet of them. If the target\
    \ can hear the godcaller, the target can use their reaction to move up to their\
    \ speed and make an attack."
  "name": "Cadenza"
- "desc": "The godcaller and each ally within 30 feet of them who can hear them has\
    \ advantage on attack rolls until the start of the godcaller's next turn. This\
    \ effect ends early if the godcaller takes any damage."
  "name": "Song of the Gods (2nd-Level Spell)"
"bonus_actions":
- "desc": "The godcaller and up to three allies within 60 feet of them who can hear\
    \ them regain 20 hit points, and these creatures ignore difficult terrain for\
    \ 1 minute."
  "name": "Rallying Ostinato (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Orc%20Godcaller.png"
```
^statblock