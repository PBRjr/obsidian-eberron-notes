---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/harpy
- ttrpg-cli/monster/type/monstrosity/retainer
statblock: inline
aliases: ["Harpy Fledgling"]
---
# [Harpy Fledgling](Misc Files\CLI\compendium\bestiary\monstrosity/harpy-fledgling-fleemortals.md)
*Source: Flee, Mortals! p. 143*  

```statblock
"name": "Harpy Fledgling (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Harpy, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "12"
"speed": "30 ft., fly 30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Athletics": !!int "0"
  "Performance": !!int "0"
"senses": "blindsight 15 ft., passive Perception 10"
"languages": "Common, Giant"
"traits":
- "desc": "The harpy can't use their blindsight while [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened)."
  "name": "Echolocation"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 2d4 plus PB slashing damage. Beginning at 7th level, the fledgling can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Talons)"
- "desc": "As a bonus action, the fledgling moves up to their flying speed without\
    \ provoking opportunity attacks. If they end this movement within 5 feet of an\
    \ enemy they can see, the fledgling can make a signature attack against them."
  "name": "3rd Level: Wind Sweep (3/Day)"
- "desc": "When the fledgling hits a Medium or smaller creature with a signature attack,\
    \ the target is also [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). The fledging then moves up to their fly speed without\
    \ provoking opportunity attacks (no action required). While grappling the target,\
    \ the fledgling can't attack another creature."
  "name": "5th Level: Food Grab (3/Day)"
- "desc": "As an action, the fledgling starts singing for 1 minute. Each creature\
    \ within 60 feet of the fledgling who can hear them and who understands Common\
    \ or Giant must succeed on a DC 10 plus PB Wisdom saving throw or be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by the fledgling until they can't hear the fledgling singing anymore. While\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed) in this way, a creature\
    \ can't willingly harm any of the fledgling's allies."
  "name": "7th Level: Harpy Song (1/Day)"
"source":
- "FleeMortals"
```
^statblock