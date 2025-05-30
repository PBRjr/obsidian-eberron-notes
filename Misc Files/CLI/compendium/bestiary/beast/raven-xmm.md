---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast
statblock: inline
aliases: ["Raven"]
---
# [Raven](Misc Files\CLI\compendium\bestiary\beast/raven-xmm.md)
*Source: Monster Manual (2024) p. 368, Player's Handbook (2024) p. 355*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Misc%20Files/CLI/compendium/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Misc%20Files/CLI/compendium/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Raven (XMM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "2"
"hit_dice": "1d4"
"stats":
- !!int "2"
- !!int "14"
- !!int "10"
- !!int "5"
- !!int "13"
- !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The raven can mimic simple sounds it has heard, such as a whisper or chitter.\
    \ A hearer can discern the sounds are imitations with a successful DC 10 Wisdom\
    \ ([Insight](Misc%20Files/CLI/rules/skills.md#Insight)) check."
  "name": "Mimicry"
"actions":
- "desc": "Melee Attack Roll: +4, reach 5 ft. Hit: 1 Piercing damage."
  "name": "Beak"
"source":
- "XMM"
- "XPHB"
"image": "Misc%20Files/CLI/compendium/bestiary/beast/token/raven-xmm.webp"
```
^statblock

## Environment

hill, swamp, urban