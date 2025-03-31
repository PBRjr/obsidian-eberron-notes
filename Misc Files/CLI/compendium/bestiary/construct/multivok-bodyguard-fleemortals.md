---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct/soldier
statblock: inline
aliases: ["Multivok Bodyguard"]
---
# [Multivok Bodyguard](Misc Files\CLI\compendium\bestiary\construct/multivok-bodyguard-fleemortals.md)
*Source: Flee, Mortals! p. 276*  

```statblock
"name": "Multivok Bodyguard (FleeMortals)"
"size": "Large"
"type": "construct"
"subtype": "Soldier"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"stats":
- !!int "21"
- !!int "10"
- !!int "18"
- !!int "7"
- !!int "12"
- !!int "3"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "3"
  "Strength": !!int "8"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "8"
  "Perception": !!int "7"
"damage_resistances": "psychic; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Dwarvish"
"cr": "8"
"traits":
- "desc": "The bodyguard is immune to any power, spell, or effect that would alter\
    \ their form."
  "name": "Immutable Form"
- "desc": "The bodyguard has advantage on saving throws against powers, spells, and\
    \ other supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "The bodyguard makes three attacks using Axe Arm, Repeating Crossbow, or\
    \ both."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 18\
    \ (2d12 + 5) slashing damage. If the target is wielding at least one weapon,\
    \ they must make a DC 16 Strength saving throw. On a failed save, the target drops\
    \ one weapon they wield of the bodyguard's choice, and the bodyguard kicks it\
    \ up to 15 feet away."
  "name": "Axe Arm"
- "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
    \ 16 (3d10) piercing damage."
  "name": "Repeating Crossbow"
"bonus_actions":
- "desc": "Each enemy wearing metal armor or made of metal within 30 feet of the bodyguard\
    \ must succeed on a DC 15 Strength saving throw or be pulled up to 15 feet toward\
    \ the bodyguard."
  "name": "Magnetic Pull"
"reactions":
- "desc": "When an attack hits a Medium or smaller ally the bodyguard can see within\
    \ 5 feet of them, the bodyguard forces the attacker to reroll the attack against\
    \ the bodyguard instead."
  "name": "Valiar Cloak"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Multivok%20Bodyguard.png"
```
^statblock