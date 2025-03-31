---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct/brute
statblock: inline
aliases: ["Servok Builder"]
---
# [Servok Builder](Misc Files\CLI\compendium\bestiary\construct/servok-builder-fleemortals.md)
*Source: Flee, Mortals! p. 278*  

```statblock
"name": "Servok Builder (FleeMortals)"
"size": "Huge"
"type": "construct"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d12 + 112"
"stats":
- !!int "25"
- !!int "6"
- !!int "24"
- !!int "3"
- !!int "8"
- !!int "1"
"speed": "20 ft."
"saves":
  "Strength": !!int "11"
  "Constitution": !!int "11"
"skillsaves":
  "Athletics": !!int "11"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "understands Dwarvish but can't speak"
"cr": "12"
"traits":
- "desc": "The builder is immune to any power, spell, or effect that would alter their\
    \ form."
  "name": "Immutable Form"
- "desc": "The builder deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The builder has advantage on saving throws against powers, spells, and\
    \ other supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "The builder makes two attacks using Wrecking Ball, Stone, or both, and\
    \ can use Lay the Foundation, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 26\
    \ (3d12 + 7) bludgeoning damage.\n\nEach enemy within 5 feet of the target must\
    \ succeed on a DC 19 Dexterity saving throw or take 13 (2d12) bludgeoning damage."
  "name": "Wrecking Ball"
- "desc": "Melee or Ranged Weapon Attack: +11 to hit, reach 10 ft. or range 60/240\
    \ ft., one target. Hit: 23 (3d10 + 7) bludgeoning damage. If the target is\
    \ a Medium or smaller creature, they are knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Stone"
- "desc": "The builder pours wet concrete on the ground in a 20-foot square starting\
    \ from a point within 5 feet of the builder. Until the foundation dries in 1 hour,\
    \ that area is difficult terrain, and when a creature with a Strength score of\
    \ 20 or less starts their turn in that area, they must succeed on a DC 19 Strength\
    \ ([Athletics](Misc%20Files/CLI/rules/skills.md#Athletics)) check or be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ until the start of their next turn."
  "name": "Lay the Foundation (Recharge 6)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Servok%20Builder.png"
```
^statblock