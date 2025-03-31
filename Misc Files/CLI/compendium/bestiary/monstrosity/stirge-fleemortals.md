---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/monstrosity/controller
statblock: inline
aliases: ["Stirge"]
---
# [Stirge](Misc Files\CLI\compendium\bestiary\monstrosity/stirge-fleemortals.md)
*Source: Flee, Mortals! p. 226*  

```statblock
"name": "Stirge (FleeMortals)"
"size": "Tiny"
"type": "monstrosity"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "4"
"hit_dice": "1d4 + 2"
"stats":
- !!int "4"
- !!int "17"
- !!int "14"
- !!int "3"
- !!int "10"
- !!int "2"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "5"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "If the stirge is reduced to 0 hit points by any damage other than psychic\
    \ while attached to another creature, that creature takes damage equal to half\
    \ that dealt to the stirge."
  "name": "Tiny Target"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 3\
    \ piercing damage, and the stirge can attach to the target and enter their space.\
    \ While attached, the stirge moves with the target and can't make Proboscis attacks.\
    \ A creature who can reach the stirge can use an action to detach the stirge,\
    \ shunting them into the nearest unoccupied space of the stirge's choice. The\
    \ stirge also detaches if they become [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled),\
    \ [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated), [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
    \ or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)."
  "name": "Proboscis"
- "desc": "The stirge sips the life essence of a creature they are attached to who\
    \ isn't a Construct or an Undead. The creature loses 3 hit points and must succeed\
    \ on a DC 12 Constitution saving throw or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ until the end of the stirge's next turn. If the creature is already [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned),\
    \ they also become [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed) until the\
    \ end of the stirge's next turn."
  "name": "Drain Essence"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Stirge.png"
```
^statblock