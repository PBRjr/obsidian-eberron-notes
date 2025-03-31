---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant/controller
- ttrpg-cli/monster/type/plant/fungus
statblock: inline
aliases: ["Deep Dreamer"]
---
# [Deep Dreamer](Misc Files\CLI\compendium\bestiary\plant/deep-dreamer-fleemortals.md)
*Source: Flee, Mortals! p. 340*  

```statblock
"name": "Deep Dreamer (FleeMortals)"
"size": "Large"
"type": "plant"
"subtype": "fungus, Controller"
"alignment": "typically  Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "21d10 + 63"
"stats":
- !!int "17"
- !!int "10"
- !!int "16"
- !!int "20"
- !!int "12"
- !!int "16"
"speed": "0 ft., fly 20 ft. (hover)"
"saves":
  "Intelligence": !!int "10"
"skillsaves":
  "Deception": !!int "8"
  "Insight": !!int "6"
  "Persuasion": !!int "8"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Deep Speech, Undercommon, telepathy 120 ft."
"cr": "13"
"traits":
- "desc": "The dreamer is immune to divination spells and to any effect that would\
    \ sense their emotions or read their thoughts."
  "name": "Psionic Shroud"
"actions":
- "desc": "The dreamer makes two Tendrils attacks and uses Dream Spores, if available."
  "name": "Multiattack"
- "desc": "Melee Power Attack: +10 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage plus 22 (4d10) psychic damage. If the target is\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed) by the dreamer, the\
    \ dreamer regains hit points equal to half the psychic damage dealt."
  "name": "Tendrils"
- "desc": "The dreamer releases a cloud of psionic spores. Each creature within 60\
    \ feet of them must succeed on a DC 18 Intelligence saving throw or be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by the dreamer for 1 minute.\n\nWhile [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ in this way, a creature must use their movement during their turn to move within\
    \ 10 feet of the dreamer by the safest available route.\n\nA creature [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ in this way can repeat the saving throw whenever they take damage, ending the\
    \ effect on themself on a success."
  "name": "*Dream Spores (5th-Order Power; Recharge 5-6)"
"reactions":
- "desc": "When a creature makes an attack against the dreamer, the dreamer chooses\
    \ a creature [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed) by the dreamer\
    \ within the attack's range, and the [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ creature becomes the target of the attack instead."
  "name": "Rouse Dreamer"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Deep%20Dreamer.png"
```
^statblock