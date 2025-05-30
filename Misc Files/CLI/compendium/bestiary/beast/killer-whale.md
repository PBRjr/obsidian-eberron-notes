---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Killer Whale"]
---
# [Killer Whale](Misc Files\CLI\compendium\bestiary\beast/killer-whale.md)
*Source: Monster Manual p. 331. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Killer Whale"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d12 + 12"
"stats":
- !!int "19"
- !!int "10"
- !!int "13"
- !!int "3"
- !!int "12"
- !!int "7"
"speed": "swim 60 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "blindsight 120 ft., passive Perception 13"
"languages": ""
"cr": "3"
"traits":
- "desc": "The whale can't use its blindsight while [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened)."
  "name": "Echolocation"
- "desc": "The whale can hold its breath for 30 minutes."
  "name": "Hold Breath"
- "desc": "The whale has advantage on Wisdom ([Perception](Misc%20Files/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing."
  "name": "Keen Hearing"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 21\
    \ (5d6 + 4) piercing damage."
  "name": "Bite"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/beast/token/killer-whale.webp"
```
^statblock

## Environment

underwater