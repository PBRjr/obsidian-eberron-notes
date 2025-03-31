---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/soldier
statblock: inline
aliases: ["Fire Giant Red Fist"]
---
# [Fire Giant Red Fist](Misc Files\CLI\compendium\bestiary\giant/fire-giant-red-fist-fleemortals.md)
*Source: Flee, Mortals! p. 106*  

```statblock
"name": "Fire Giant Red Fist (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Soldier"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "162"
"hit_dice": "13d12 + 78"
"stats":
- !!int "25"
- !!int "14"
- !!int "23"
- !!int "10"
- !!int "14"
- !!int "13"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "6"
  "Strength": !!int "11"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "6"
"damage_immunities": "fire"
"senses": "passive Perception 16"
"languages": "Giant"
"cr": "9"
"traits":
- "desc": "When an enemy moves out of the red fist's reach, the enemy must succeed\
    \ on a DC 18 Constitution saving throw or gain a level of [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion).\
    \ Creatures with resistance or immunity to fire damage are immune to this effect."
  "name": "Heat and Pressure"
- "desc": "The first time a creature other than a fire giant touches the red fist\
    \ or hits them with a melee attack on a turn, that creature takes 7 (2d6) fire\
    \ damage."
  "name": "Molten Flesh"
"actions":
- "desc": "The red fist makes two Unarmed Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 21\
    \ (4d6 + 7) bludgeoning damage plus 7 (2d6) fire damage. If the same creature\
    \ is hit twice with this attack on a turn, they are [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)\
    \ until the end of their next turn."
  "name": "Unarmed Strike"
- "desc": "Ranged Spell Attack: +10 to hit, range 180 ft., one target. Hit:\
    \ 34 (8d6 + 6) fire damage."
  "name": "Hurl Flame"
"reactions":
- "desc": "When an enemy within 10 feet of the red fist hits a creature other than\
    \ the red fist with an attack, the red fist halves the damage dealt by that attack.\
    \ The red fist then makes an Unarmed Strike against the attacker."
  "name": "Guardian Block (3/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Fire%20Giant%20Red%20Fist.png"
```
^statblock