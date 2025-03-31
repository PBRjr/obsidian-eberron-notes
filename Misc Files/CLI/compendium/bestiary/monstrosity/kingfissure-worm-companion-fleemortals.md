---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
aliases: ["Kingfissure Worm Companion"]
---
# [Kingfissure Worm Companion](Misc Files\CLI\compendium\bestiary\monstrosity/kingfissure-worm-companion-fleemortals.md)
*Source: Flee, Mortals! p. 169*  

```statblock
"name": "Kingfissure Worm Companion (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "8"
- !!int "14"
- !!int "3"
- !!int "10"
- !!int "6"
"speed": "30 ft., burrow 30 ft."
"saves":
  "Dexterity": !!int "0"
  "Strength": !!int "0"
"skillsaves":
  "Athletics": !!int "0"
  "Perception": !!int "0"
"senses": "darkvision 30 ft., tremorsense 60 ft., passive Perception 0"
"languages": ""
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB acid damage."
  "name": "Signature Attack (Tongue Lash)"
- "desc": "The worm makes a signature attack. On a hit, the attack deals its normal\
    \ effects, and the next attack roll made against the target before the start of\
    \ the worm's next turn has advantage."
  "name": "1st Level: Distracting Attack (2 Ferocity)"
- "desc": "The worm makes a signature attack. On a hit, the target is also [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). Until this grapple ends, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and the worm can't make a signature attack against another target."
  "name": "3rd Level: Tongue Grab (5 Ferocity)"
- "desc": "The worm attempts to swallow a Medium or smaller creature within 5 feet\
    \ of them. The target must make a DC 10 plus PB Dexterity saving throw. On a failed\
    \ save, the target takes PBd6 bludgeoning damage and is swallowed. On a successful\
    \ save, the target takes half as much damage and isn't swallowed. The worm can\
    \ have only one target swallowed at a time.\n\nA swallowed target is [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)\
    \ and [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained), they have\
    \ total cover against attacks and other effects outside the worm, and they take\
    \ PBd6 acid damage at the start of each of the worm's turns. Whenever the worm\
    \ takes damage, they must succeed on a Constitution saving throw or regurgitate\
    \ the swallowed creature, who falls [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ in an unoccupied space within 5 feet of the worm. The DC for this saving throw\
    \ equals 10 or half the triggering damage, whichever is higher. If the worm is\
    \ [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated) or dies,\
    \ a swallowed creature is no longer [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ by the worm and can escape from the corpse using 5 feet of movement, exiting\
    \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "5th Level: Swallow (8 Ferocity)"
"bonus_actions":
- "desc": "The worm can swallow an object without harming it by storing the object\
    \ in a second stomach. They can use this bonus action again to regurgitate a specific\
    \ stored object without disturbing any other objects in their second stomach.\
    \ A regurgitated object lands in an unoccupied space within 5 feet of the worm.\n\
    \nThe worm's second stomach can hold up to PB × 10 pounds of objects, not exceeding\
    \ a volume of 10 cubic feet."
  "name": "Item Storage"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Kingfissure%20Worm%20Companion.png"
```
^statblock