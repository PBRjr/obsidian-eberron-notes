---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Warhorse"]
---
# [Warhorse](Misc Files\CLI\compendium\bestiary\beast/warhorse-xmm.md)
*Source: Monster Manual (2024) p. 373, Player's Handbook (2024) p. 359*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Misc%20Files/CLI/compendium/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Misc%20Files/CLI/compendium/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Warhorse (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "18"
- !!int "12"
- !!int "13"
- !!int "2"
- !!int "12"
- !!int "7"
"speed": "60 ft."
"saves":
  "Wisdom": !!int "3"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"actions":
- "desc": "Melee Attack Roll: +6, reach 5 ft. Hit: 9 (2d4 + 4) Bludgeoning\
    \ damage. If the target is a Large or smaller creature and the horse moved 20+\
    \ feet straight toward it immediately before the hit, the target takes an extra\
    \ 5 (2d4) Bludgeoning damage and has the [Prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ condition."
  "name": "Hooves"
"source":
- "XMM"
- "XPHB"
"image": "Misc%20Files/CLI/compendium/bestiary/beast/token/warhorse-xmm.webp"
```
^statblock

## Environment

urban