---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Elk"]
---
# [Elk](Misc Files\CLI\compendium\bestiary\beast/elk-xmm.md)
*Source: Monster Manual (2024) p. 353, Player's Handbook (2024) p. 349*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Misc%20Files/CLI/compendium/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Misc%20Files/CLI/compendium/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Elk (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "11"
"hit_dice": "2d10"
"stats":
- !!int "16"
- !!int "10"
- !!int "11"
- !!int "2"
- !!int "10"
- !!int "6"
"speed": "50 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "Melee Attack Roll: +5, reach 5 ft. Hit: 6 (1d6 + 3) Bludgeoning\
    \ damage. If the target is a Large or smaller creature and the elk moved 20+ feet\
    \ straight toward it immediately before the hit, the target takes an extra 3 (1d6)\
    \ Bludgeoning damage and has the [Prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Ram"
"source":
- "XMM"
- "XPHB"
"image": "Misc%20Files/CLI/compendium/bestiary/beast/token/elk-xmm.webp"
```
^statblock

## Environment

forest, grassland, hill