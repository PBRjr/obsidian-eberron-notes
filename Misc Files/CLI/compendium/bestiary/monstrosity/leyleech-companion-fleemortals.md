---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
aliases: ["Leyleech Companion"]
---
# [Leyleech Companion](Misc Files\CLI\compendium\bestiary\monstrosity/leyleech-companion-fleemortals.md)
*Source: Flee, Mortals! p. 344*  

```statblock
"name": "Leyleech Companion (FleeMortals)"
"size": "Small"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "5"
- !!int "12"
- !!int "8"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
"skillsaves":
  "Perception": !!int "0"
"condition_immunities": "[prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "darkvision 120 ft., passive Perception 0"
"languages": ""
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB piercing damage."
  "name": "Signature Attack (Bite)"
- "desc": "The leyleech makes a signature attack. On a hit, the attack deals an extra\
    \ PB damage, and if the target hits the leyleech with an attack before the start\
    \ of the leyleech's next turn, the target takes PB lightning damage."
  "name": "1st Level: Sparking Attack (2 Ferocity)"
- "desc": "The area within 10 feet of the leyleech becomes difficult terrain for their\
    \ enemies until the start of their next turn. When an enemy enters that area for\
    \ the first time on a turn or starts their turn there, they must succeed on a\
    \ DC 10 plus PB Dexterity saving throw or take PBd4 force damage."
  "name": "3rd Level: Anomalous Terrain (5 Ferocity)"
- "desc": "The leyleech spews corrupted magical energy at a creature they can see\
    \ within 30 feet of them. The target must make a DC 10 plus PB Constitution saving\
    \ throw. On a failed save, the target takes PBd8 force damage and is [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed)\
    \ until the start of the leyleech's next turn. On a successful save, the target\
    \ takes half as much damage and isn't [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed)."
  "name": "5th Level: Magic Purge (8 Ferocity)"
"reactions":
- "desc": "When the leyleech's caregiver is within 30 feet of them and the leyleech\
    \ or their caregiver is affected by a spell of 3rd level or lower, the leyleech\
    \ consumes the spell's magic, and it has no effect on the leyleech and their caregiver."
  "name": "Absorb Magic (Recharges after a Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Leyleech%20Companion.png"
```
^statblock