---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Basilisk"]
---
# [Basilisk](Misc Files\CLI\compendium\bestiary\monstrosity/basilisk.md)
*Source: Monster Manual p. 24. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Travelers sometimes find objects that look like pieces of remarkably lifelike stone carvings of wildlife. Missing parts appear to have been bitten off. Seasoned explorers regard such relics as warnings, knowing that the basilisk that created them is likely to be nearby.

## Adaptable Predators

Basilisks thrive in arid, temperate, or tropical climates. They lair in caves or other sheltered sites. Most often, basilisks are encountered underground.

A basilisk born and raised in captivity can be domesticated and trained. Such a trained basilisk knows how to avoid meeting the eyes of those its master wishes to protect from its gaze, but it makes a daunting guardian beast. Because of this use, basilisk eggs are highly prized.

## Gaze of Stone

Basilisks are ponderous for hunting creatures, but they needn't chase prey. Meeting a basilisk's supernatural gaze can be enough to affect a rapid transformation, transforming a victim into porous stone. Basilisks, with their strong jaws, are able to consume the stone. The stone returns to organic form in the basilisk's gullet.

Some alchemists are said to know how to process the basilisk's gullet and the fluids contained within. Properly handled, the gullet produces an oil that can return [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified) creatures to flesh and life. Unfortunately for such a victim, any parts lost in stone form remain absent if the creature revives. Revivification using the oil is impossible if a vital part of the [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified) creature, such as its head, is detached.

> [!quote] A quote from X the Mystic's 4th rule of dungeon survival  
> 
> No one carves statues of frightened warriors. If you see one, keep your eyes closed and your ears open.


```statblock
"name": "Basilisk"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "8"
- !!int "15"
- !!int "2"
- !!int "8"
- !!int "7"
"speed": "20 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "3"
"traits":
- "desc": "If a creature starts its turn within 30 feet of the basilisk and the two\
    \ of them can see each other, the basilisk can force the creature to make a DC\
    \ 12 Constitution saving throw if the basilisk isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated).\
    \ On a failed save, the creature magically begins to turn to stone and is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained).\
    \ It must repeat the saving throw at the end of its next turn. On a success, the\
    \ effect ends. On a failure, the creature is [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified)\
    \ until freed by the  [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell or other magic.\n\nA creature that isn't [surprised](Misc%20Files/CLI/rules/conditions.md#Surprised)\
    \ can avert its eyes to avoid the saving throw at the start of its turn. If it\
    \ does so, it can't see the basilisk until the start of its next turn, when it\
    \ can avert its eyes again. If it looks at the basilisk in the meantime, it must\
    \ immediately make the save.\n\nIf the basilisk sees its reflection within 30\
    \ feet of it in bright light, it mistakes itself for a rival and targets itself\
    \ with its gaze."
  "name": "Petrifying Gaze"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage plus 7 (2d6) poison damage."
  "name": "Bite"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/monstrosity/token/basilisk.webp"
```
^statblock

## Environment

mountain