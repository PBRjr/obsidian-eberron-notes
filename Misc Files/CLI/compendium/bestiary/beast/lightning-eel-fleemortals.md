---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/artillery
statblock: inline
aliases: ["Lightning Eel"]
---
# [Lightning Eel](Misc Files\CLI\compendium\bestiary\beast/lightning-eel-fleemortals.md)
*Source: Flee, Mortals! p. 40*  

```statblock
"name": "Lightning Eel (FleeMortals)"
"size": "Medium"
"type": "beast"
"subtype": "Artillery"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "12"
- !!int "15"
- !!int "14"
- !!int "5"
- !!int "10"
- !!int "4"
"speed": "15 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "4"
"skillsaves":
  "Perception": !!int "2"
  "Acrobatics": !!int "6"
"damage_immunities": "lightning"
"senses": "passive Perception 12"
"languages": ""
"cr": "2"
"traits":
- "desc": "The eel can breathe air and water. They can survive out of water for up\
    \ to 8 hours."
  "name": "Amphibious"
- "desc": "The eel has advantage on ability checks and saving throws made to avoid\
    \ or end the [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) condition\
    \ on themself."
  "name": "Slippery"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "The eel channels energy toward a creature within 20 feet of them. The target\
    \ must make a DC 12 Constitution saving throw, made with disadvantage if the target\
    \ is touching the eel. On a failed save, a creature takes 18 (4d8) lightning\
    \ damage and is [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed) until the\
    \ end of their next turn. On a successful save, a creature takes half as much\
    \ damage and isn't [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed)."
  "name": "Electric Pulse"
"source":
- "FleeMortals"
```
^statblock