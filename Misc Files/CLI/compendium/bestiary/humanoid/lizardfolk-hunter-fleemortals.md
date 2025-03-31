---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/lizardfolk
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
aliases: ["Lizardfolk Hunter"]
---
# [Lizardfolk Hunter](Misc Files\CLI\compendium\bestiary\humanoid/lizardfolk-hunter-fleemortals.md)
*Source: Flee, Mortals! p. 185*  

```statblock
"name": "Lizardfolk Hunter (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
- !!int "10"
"speed": "30 ft., swim 30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Nature": !!int "0"
  "Athletics": !!int "0"
  "Perception": !!int "0"
"senses": "passive Perception 0"
"languages": "Common, Draconic"
"actions":
- "desc": "Melee Attack Roll: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 2d6 plus PB slashing damage. Beginning at 7th level, the hunter can make this\
    \ attack twice, instead of once, when they take the Attack action on their turn."
  "name": "Signature Attack (Greatsword)"
- "desc": "As an action, the hunter makes a signature attack against a Large or smaller\
    \ creature. On a hit, the target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). Until the grapple ends, the target takes PB piercing\
    \ damage at the end of each of their turns, and the hunter can't use their Wrenching\
    \ Bite against another target."
  "name": "3rd Level: Wrenching Bite (3/Day)"
- "desc": "As an action, the hunter makes a signature attack against a Large or smaller\
    \ creature. On a hit, the target must succeed on a DC 10 plus PB Dexterity saving\
    \ throw or fall [prone](Misc%20Files/CLI/rules/conditions.md#Prone). While the\
    \ hunter is within 5 feet of this [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ target, the target can't stand up unless they use an action to make a DC 10\
    \ plus PB Strength ([Athletics](Misc%20Files/CLI/rules/skills.md#Athletics)) check.\
    \ On a success, the target can stand up."
  "name": "5th Level: Thrashing Tail (3/Day)"
- "desc": "As a bonus action, the hunter drones lullingly. Each creature within 5\
    \ feet of the hunter who can hear them must succeed on a DC 10 plus PB Constitution\
    \ saving throw or fall [unconscious](Misc%20Files/CLI/rules/conditions.md#Unconscious)\
    \ for 1 minute. An [unconscious](Misc%20Files/CLI/rules/conditions.md#Unconscious)\
    \ target wakes up if they take damage, the hunter becomes [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ the hunter moves more than 5 feet away from the target, or another creature\
    \ uses an action to rouse the target."
  "name": "7th Level: Hypnotic Sleep (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Lizardfolk%20Hunter.png"
```
^statblock