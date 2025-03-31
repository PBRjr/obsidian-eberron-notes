---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dwarf
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
aliases: ["Jutkarr Flintfingers"]
---
# [Jutkarr Flintfingers](Misc Files\CLI\compendium\bestiary\npc/jutkarr-flintfingers-fleemortals.md)
*Source: Flee, Mortals! p. 376*  

```statblock
"name": "Jutkarr Flintfingers (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf, Support"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[breastplate](Misc%20Files/CLI/compendium/items/breastplate-xphb.md)"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "13"
- !!int "15"
- !!int "14"
- !!int "22"
- !!int "16"
- !!int "7"
"speed": "25 ft."
"saves":
  "Intelligence": !!int "9"
  "Constitution": !!int "5"
"skillsaves":
  "Investigation": !!int "9"
  "Religion": !!int "9"
  "Perception": !!int "6"
  "History": !!int "9"
"damage_resistances": "poison, psychic"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Dwarvish, thieves' cant, telepathy 120 ft."
"cr": "5"
"traits":
- "desc": "Jutkarr can communicate telepathically with any Amethyst Knife boss regardless\
    \ of distance, provided they are on the same plane of existence."
  "name": "Mind Link"
- "desc": "Jutkarr has advantage on saving throws he makes to avoid or end the [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ condition on himself."
  "name": "Poison Resistant"
"actions":
- "desc": "Jutkarr makes two Deserved Transfer attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Power Attack: +9 to hit, reach 5 ft. or range 30 ft.,\
    \ one creature. Hit: 13 (2d6 + 6) psychic damage, and one creature Jutkarr\
    \ can see within 30 feet of him gains temporary hit points equal to half the damage\
    \ dealt."
  "name": "*Deserved Transfer (2nd-Order Power)"
- "desc": "Jutkarr touches a willing creature and gives them immunity to one of the\
    \ following conditions for 1 hour: [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
    \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned), or [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned).\
    \ Additionally, if the target suffers from the chosen condition, that condition\
    \ is suppressed for 1 hour."
  "name": "Psionic Resilience (2/Day; 4th-Order Power)"
"reactions":
- "desc": "When Jutkarr is [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), or [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned),\
    \ he chooses a willing Amethyst Knife boss within 60 feet of him who doesn't already\
    \ have the condition or is immune to it. The chosen creature then gains the condition\
    \ for the duration, and Jutkarr loses the condition. He can use this reaction\
    \ even while [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)."
  "name": "Shared Condition"
"source":
- "FleeMortals"
```
^statblock