---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Noble"]
---
# [Noble](Misc Files\CLI\compendium\bestiary\humanoid/noble.md)
*Source: Monster Manual p. 348, Eberron: Rising from the Last War. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Nobles wield great authority and influence as members of the upper class, possessing wealth and connections that can make them as powerful as monarchs and generals. A noble often travels in the company of guards, as well as servants who are commoners.

The noble's statistics can also be used to represent courtiers who aren't of noble birth.

```statblock
"name": "Noble"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[breastplate](Misc%20Files/CLI/compendium/items/breastplate-xphb.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Insight": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 12"
"languages": "any two languages"
"cr": "1/8"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) piercing damage."
  "name": "Rapier"
"reactions":
- "desc": "The noble adds 2 to its AC against one melee attack that would hit it.\
    \ To do so, the noble must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "MM"
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/humanoid/token/noble.webp"
```
^statblock

## Environment

urban