---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
statblock: inline
aliases: ["Helmed Horror"]
---
# [Helmed Horror](Misc Files\CLI\compendium\bestiary\construct/helmed-horror.md)
*Source: Monster Manual p. 183*  

This construct possesses intelligence, the ability to reason and adjust its tactics, and an unswerving devotion to its maker that persists even after its maker's demise. Resembling an animated suit of empty plate armor, a helmed horror serves without ambition or emotion.

## Magical Purpose

Though it takes more magical resources to create a helmed horror than a lesser suit of animated armor, the helmed horror requires less direction and maintenance as it carries out its appointed tasks. A helmed horror follows its orders with complete loyalty, and is intelligent enough to understand the difference between an order's intent and its exact wording. Unlike many constructs, it seeks to fulfill the former rather than slavishly follow the latter.

## Tactical Cunning

A helmed horror fights with the cunning of a skilled warrior, taking to the air as it attacks weaker characters and spellcasters first. However, a helmed horror lacks the insight to change its environment, fortify it, or otherwise take active measures to improve its defensive position.

## Constructed Nature

A helmed horror doesn't require air, food, drink, or sleep.

```statblock
"name": "Helmed Horror"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate armor](Misc%20Files/CLI/compendium/items/plate-armor-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"stats":
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Perception": !!int "4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "force, necrotic, poison"
"condition_immunities": "[blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
  \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned),\
  \ [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 14"
"languages": "understands the languages of its creator but can't speak"
"cr": "4"
"traits":
- "desc": "The helmed horror has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The helmed horror is immune to three spells chosen by its creator. Typical\
    \ immunities include [fireball](Misc%20Files/CLI/compendium/spells/fireball-xphb.md),\
    \ [heat metal](Misc%20Files/CLI/compendium/spells/heat-metal-xphb.md), and [lightning\
    \ bolt](Misc%20Files/CLI/compendium/spells/lightning-bolt-xphb.md)."
  "name": "Spell Immunity"
"actions":
- "desc": "The helmed horror makes two longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands."
  "name": "Longsword"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/construct/token/helmed-horror.webp"
```
^statblock