---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Weasel"]
---
# [Weasel](Misc Files\CLI\compendium\bestiary\beast/weasel-xmm.md)
*Source: Monster Manual (2024) p. 372, Player's Handbook (2024) p. 359*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Misc%20Files/CLI/compendium/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Misc%20Files/CLI/compendium/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Weasel (XMM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "3"
- !!int "16"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "3"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "3"
  "Acrobatics": !!int "5"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "0"
"actions":
- "desc": "Melee Attack Roll: +5, reach 5 ft. Hit: 1 Piercing damage."
  "name": "Bite"
"source":
- "XMM"
- "XPHB"
"image": "Misc%20Files/CLI/compendium/bestiary/beast/token/weasel-xmm.webp"
```
^statblock

## Environment

forest, grassland, hill