---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/bugbear
statblock: inline
aliases: ["Bugbear Predator"]
---
# [Bugbear Predator](Misc Files\CLI\compendium\bestiary\humanoid/bugbear-predator-fleemortals.md)
*Source: Flee, Mortals! p. 52*  

```statblock
"name": "Bugbear Predator (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "bugbear, Ambusher"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](Misc%20Files/CLI/compendium/items/leather-armor-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "15"
- !!int "17"
- !!int "15"
- !!int "13"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
  "Survival": !!int "4"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Goblin"
"cr": "3"
"traits":
- "desc": "Allied Humanoids within 15 feet of the predator who can see or hear them\
    \ have advantage on Wisdom and Charisma saving throws."
  "name": "Bugbear's Inspiration"
- "desc": "When the predator hits a creature with a melee weapon attack and has advantage\
    \ on the attack roll, the target must succeed on a DC 12 Constitution saving throw\
    \ or be [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded) until the end\
    \ of their next turn."
  "name": "Dirty Fighting"
"actions":
- "desc": "The predator makes two Curved Dagger or two Longbow attacks. If both attacks\
    \ hit the same target, the predator has advantage on their next attack roll made\
    \ against the target before the end of the predator's next turn."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 8 (2d4 + 3) piercing damage."
  "name": "Curved Dagger"
- "desc": "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage."
  "name": "Longbow"
- "desc": "Each ally within 30 feet of the predator who can hear and understand them\
    \ gains the predator's Dirty Fighting trait until the start of the predator's\
    \ next turn."
  "name": "Go for the Eyes (1/Day)"
"bonus_actions":
- "desc": "The predator takes the Dash or Hide action."
  "name": "Guerilla Training"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Bugbear%20Predator.png"
```
^statblock