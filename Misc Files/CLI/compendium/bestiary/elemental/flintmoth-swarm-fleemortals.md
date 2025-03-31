---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/elemental/brute
statblock: inline
aliases: ["Flintmoth Swarm"]
---
# [Flintmoth Swarm](Misc Files\CLI\compendium\bestiary\elemental/flintmoth-swarm-fleemortals.md)
*Source: Flee, Mortals! p. 321*  

```statblock
"name": "Flintmoth Swarm (FleeMortals)"
"size": "Unknown"
"type": "elemental"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d12 + 32"
"stats":
- !!int "13"
- !!int "20"
- !!int "15"
- !!int "1"
- !!int "8"
- !!int "1"
"speed": "20 ft., climb 20 ft., fly 40 ft."
"saves":
  "Dexterity": !!int "9"
"skillsaves":
  "Stealth": !!int "9"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), flanked, [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned),\
  \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone), [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained),\
  \ [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned)"
"senses": "blindsight 15 ft., darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "11"
"traits":
- "desc": "Other creatures in the swarm's space are [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)."
  "name": "Obscuring Form"
- "desc": "When the swarm is reduced to half their hit points, their size becomes\
    \ Large."
  "name": "Shrink"
- "desc": "The swarm has advantage on Dexterity ([Stealth](Misc%20Files/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in rocky terrain."
  "name": "Stone Camouflage"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny insect. The swarm can't\
    \ regain hit points or gain temporary hit points."
  "name": "Swarm"
"actions":
- "desc": "The swarm makes three Flutter Cutter attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 26 (6d6 + 5) slashing damage, or 33 (8d6 + 5) slashing damage\
    \ if the target is a Construct made of stone or is holding or wearing an object\
    \ that emits bright light."
  "name": "Flutter Cutter"
"bonus_actions":
- "desc": "The swarm feeds on a mundane object or structure within 5 feet of them\
    \ that is made mostly of stone.\n\nIf the swarm targets a Medium or smaller object,\
    \ it is entirely devoured. If the swarm targets a structure or a Large or larger\
    \ object, the swarm devours a 5-foot-cube portion of it."
  "name": "Devour Stone"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Flintmoth%20Swarm.png"
```
^statblock