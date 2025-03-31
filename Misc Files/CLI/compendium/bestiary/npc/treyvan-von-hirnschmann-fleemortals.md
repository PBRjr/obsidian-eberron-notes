---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
aliases: ["Treyvan von Hirnschmann"]
---
# [Treyvan von Hirnschmann](Misc Files\CLI\compendium\bestiary\npc/treyvan-von-hirnschmann-fleemortals.md)
*Source: Flee, Mortals! p. 377*  

```statblock
"name": "Treyvan von Hirnschmann (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf, Soldier"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate](Misc%20Files/CLI/compendium/items/plate-armor-xphb.md)"
"hp": !!int "102"
"hit_dice": "12d8 + 48"
"stats":
- !!int "22"
- !!int "8"
- !!int "18"
- !!int "11"
- !!int "14"
- !!int "22"
"speed": "30 ft."
"saves":
  "Strength": !!int "9"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "9"
  "Religion": !!int "3"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Elvish, telepathy 120 ft."
"cr": "5"
"traits":
- "desc": "Treyvan has advantage on saving throws he makes to avoid or end the [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ condition on himself."
  "name": "Charm Resistant"
- "desc": "Treyvan can communicate telepathically with any Amethyst Knife boss regardless\
    \ of distance, provided they are on the same plane of existence."
  "name": "Mind Link"
- "desc": "Each ally within 20 feet of Treyvan has a +2 bonus to AC and Dexterity\
    \ saving throws. Enemies treat the area within 20 feet of Treyvan as difficult\
    \ terrain."
  "name": "Telekinetic Bastion"
"actions":
- "desc": "Treyvan makes two Maul attacks. He can replace one attack with a use of\
    \ Telekinetic Throw or Choke, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d6 + 6) bludgeoning damage. If the target is Medium or smaller, Treyvan\
    \ can choose to either knock them [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ or push them up to 10 feet away from him."
  "name": "Maul"
- "desc": "Treyvan throws his maul with telekinetic force, making a Maul attack with\
    \ a range of 30 feet. After making this attack, the maul immediately returns to\
    \ Treyvan's hands."
  "name": "Telekinetic Throw"
- "desc": "Treyvan telekinetically crushes one Large or smaller creature he can see\
    \ within 30 feet of him. The target must succeed on a DC 17 Dexterity saving throw\
    \ or be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained) for 1 minute\
    \ (save ends at end of turn). While [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ in this way, the target takes 14 (4d6) force damage at the start of each of\
    \ their turns. If the target is ever more than 30 feet away from Treyvan or has\
    \ total cover from him, the power ends early."
  "name": "Choke (2/Day; 5th-Order Power; Concentration)"
"reactions":
- "desc": "When Treyvan is [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), or [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned),\
    \ he chooses a willing Amethyst Knife boss within 60 feet of him who doesn't already\
    \ have the condition or is immune to it. The chosen creature then gains the condition\
    \ for the duration, and Treyvan loses the condition. He can use this reaction\
    \ even while [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)."
  "name": "Shared Condition"
"source":
- "FleeMortals"
```
^statblock