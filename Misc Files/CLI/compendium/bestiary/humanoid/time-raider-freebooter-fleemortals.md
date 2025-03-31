---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/retainer
- ttrpg-cli/monster/type/humanoid/time-raider
statblock: inline
aliases: ["Time Raider Freebooter"]
---
# [Time Raider Freebooter](Misc Files\CLI\compendium\bestiary\humanoid/time-raider-freebooter-fleemortals.md)
*Source: Flee, Mortals! p. 233*  

```statblock
"name": "Time Raider Freebooter (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "time raider, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Athletics": !!int "0"
  "Perception": !!int "0"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
  \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 0"
"languages": "Common, Kuran'zoi"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d10 plus PB slashing damage. Beginning at 7th level, the freebooter can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Cutlass)"
- "desc": "As an action, the freebooter becomes [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ for 1 minute. While [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible),\
    \ the freebooter has resistance to bludgeoning, piercing, and slashing damage\
    \ from mundane attacks, and the freebooter can move through other creatures and\
    \ objects as if they were difficult terrain. The freebooter takes 5 (1d10) force\
    \ damage if they end their turn inside an object."
  "name": "7th Level: Wraithstep (1/Day)"
"bonus_actions":
- "desc": "As a bonus action, the freebooter teleports up to 30 feet to an unoccupied\
    \ space they can see. If this space is within 5 feet of an enemy the freebooter\
    \ can see, the freebooter can make a signature attack against them with advantage\
    \ as part of this bonus action."
  "name": "3rd Level: Blip Strike (3/Day)"
- "desc": "As a bonus action, the freebooter tries to telekinetically grip one creature\
    \ they can see within 60 feet of them. The target must make a DC 10 plus PB Strength\
    \ saving throw. On a failed save, the target takes PBd6 force damage and is\
    \ [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained) until the start\
    \ of the freebooter's next turn. On a successful save, the target takes half as\
    \ much damage and is not [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)."
  "name": "5th Level: Kinetic Clamp (3/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Time%20Raider%20Freebooter.png"
```
^statblock