---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/skirmisher
statblock: inline
aliases: ["Fossil Cryptic"]
---
# [Fossil Cryptic](Misc Files\CLI\compendium\bestiary\elemental/fossil-cryptic-fleemortals.md)
*Source: Flee, Mortals! p. 294*  

```statblock
"name": "Fossil Cryptic (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "earth, Skirmisher"
"alignment": "typically  Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d8 + 60"
"stats":
- !!int "19"
- !!int "14"
- !!int "18"
- !!int "12"
- !!int "13"
- !!int "10"
"speed": "40 ft., burrow 20 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "7"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned), [prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "blindsight 90 ft., passive Perception 11"
"languages": "Primordial"
"cr": "7"
"traits":
- "desc": "Prone creatures can't make opportunity attacks against the cryptic, and\
    \ the cryptic can move through spaces occupied by [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ creatures. The first time on a turn the cryptic moves through a space occupied\
    \ by a [prone](Misc%20Files/CLI/rules/conditions.md#Prone) enemy, that enemy takes\
    \ 7 (1d6 + 4) bludgeoning damage."
  "name": "Churning Trunk"
"actions":
- "desc": "The cryptic makes two Slam attacks and uses Stone Bone Storm."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "The cryptic breaks apart their body, driving a flurry of stones in a 5-foot-wide,\
    \ 30-foot-long line originating from their space. Each creature in that area must\
    \ make a DC 15 Strength saving throw, taking 18 (4d8) bludgeoning damage and\
    \ falling [prone](Misc%20Files/CLI/rules/conditions.md#Prone) on a failed save,\
    \ or taking half as much damage and not falling [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ on a successful one.\n\nThe fossil cryptic then reforms in an unoccupied space\
    \ in the line's area."
  "name": "Stone Bone Storm"
- "desc": "The cryptic burrows up to half their speed. If the cryptic ends this movement\
    \ within 5 feet of the surface, they can breach the surface. Each other creature\
    \ within 20 feet of the cryptic when they breach must make a DC 15 Dexterity saving\
    \ throw, taking 36 (8d8) bludgeoning damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Shatterstone (Recharge 6)"
"bonus_actions":
- "desc": "The cryptic shifts the ground under the feet of one creature or object\
    \ touching the ground within 30 feet of them. The target must succeed on a DC\
    \ 15 Dexterity saving throw or be moved up to 15 feet horizontally. Objects automatically\
    \ fail this saving throw."
  "name": "Stoneshift"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Fossil%20Cryptic.png"
```
^statblock