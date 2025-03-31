---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct/support
statblock: inline
aliases: ["Multivok Chief"]
---
# [Multivok Chief](Misc Files\CLI\compendium\bestiary\construct/multivok-chief-fleemortals.md)
*Source: Flee, Mortals! p. 277*  

```statblock
"name": "Multivok Chief (FleeMortals)"
"size": "Medium"
"type": "construct"
"subtype": "Support"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"stats":
- !!int "21"
- !!int "10"
- !!int "20"
- !!int "7"
- !!int "12"
- !!int "5"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Strength": !!int "10"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "10"
"damage_resistances": "psychic; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Dwarvish"
"cr": "14"
"traits":
- "desc": "The chief is immune to any power, spell, or effect that would alter their\
    \ form."
  "name": "Immutable Form"
- "desc": "The chief has advantage on saving throws against powers, spells, and other\
    \ supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "The chief makes three attacks using Pneumatic Fist, Targeting Beam, or\
    \ both."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d10 + 5) bludgeoning damage. If the target is Medium or smaller, the chief\
    \ can push them up to 10 feet away."
  "name": "Pneumatic Fist"
- "desc": "Ranged Spell Attack: +10 to hit, range 150 ft., one target. Hit:\
    \ 26 (4d12) force damage, and the target is marked by a beam of red light until\
    \ the end of the chief's next turn. While the target is marked, attack rolls against\
    \ them have advantage."
  "name": "Targeting Beam"
"bonus_actions":
- "desc": "The chief shouts a command to an ally within 60 feet of them who can hear\
    \ them. The ally can either move up to their speed without provoking opportunity\
    \ attacks or make a melee attack (no action required)."
  "name": "Chief's Command"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Multivok%20Chief.png"
```
^statblock