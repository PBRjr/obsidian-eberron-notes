---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/skirmisher
statblock: inline
aliases: ["Vampire Spawn"]
---
# [Vampire Spawn](Misc Files\CLI\compendium\bestiary\undead/vampire-spawn-fleemortals.md)
*Source: Flee, Mortals! p. 271*  

```statblock
"name": "Vampire Spawn (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Skirmisher"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "18"
- !!int "18"
- !!int "16"
- !!int "12"
- !!int "11"
- !!int "16"
"speed": "30 ft., climb 30 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "3"
"skillsaves":
  "Intimidation": !!int "6"
  "Stealth": !!int "7"
  "Perception": !!int "3"
  "Acrobatics": !!int "7"
  "Persuasion": !!int "6"
"damage_resistances": "necrotic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages they knew in life"
"cr": "5"
"traits":
- "desc": "Each time the spawn takes radiant damage, they take an extra 10 radiant\
    \ damage."
  "name": "Radiant Aversion"
"actions":
- "desc": "The spawn makes two Claw attacks. They can replace one attack with a Bite\
    \ attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage, and if the target is Large or smaller, they are\
    \ [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) (escape DC 15). Moving\
    \ while grappling a Medium or smaller creature doesn't halve the spawn's speed.\
    \ The spawn can have only one target [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way at a time."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature who is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ by the spawn, [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained). Hit: 7 (1d6\
    \ + 4) piercing damage plus 7 (2d6) necrotic damage. The target's hit point\
    \ maximum is reduced by a number equal to the necrotic damage taken, and the spawn\
    \ regains hit points equal to that number. The reduction lasts until the target\
    \ finishes a long rest or is targeted by a cure ailment power of 4th order or\
    \ higher, a [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell, or a similar supernatural effect. The target dies if this attack reduces\
    \ their hit point maximum to 0."
  "name": "Bite"
"bonus_actions":
- "desc": "The spawn moves up to their speed."
  "name": "Inhuman Speed"
"source":
- "FleeMortals"
```
^statblock