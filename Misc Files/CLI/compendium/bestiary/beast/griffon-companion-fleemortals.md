---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/companion
statblock: inline
aliases: ["Griffon Companion"]
---
# [Griffon Companion](Misc Files\CLI\compendium\bestiary\beast/griffon-companion-fleemortals.md)
*Source: Flee, Mortals! p. 135*  

```statblock
"name": "Griffon Companion (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "6"
- !!int "12"
- !!int "8"
"speed": "30 ft. (see learning to fly)"
"saves":
  "Constitution": !!int "0"
"skillsaves":
  "Perception": !!int "0"
"senses": "passive Perception 0"
"languages": ""
"traits":
- "desc": "The griffon has a flying speed of 10 × PB feet."
  "name": "Learning to Fly"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB piercing damage."
  "name": "Signature Attack (Beak)"
- "desc": "The griffon makes a signature attack. On a hit, the attack deals an extra\
    \ PB slashing damage, and the griffon can move the target 5 feet in any direction."
  "name": "1st Level: Violent Attack (2 Ferocity)"
- "desc": "The griffon makes a signature attack against a Medium or smaller creature.\
    \ On a hit, the target is also [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB) if they weren't already. While [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and the griffon can't make a signature attack against another target."
  "name": "3rd Level: Grabbed from Above (5 Ferocity)"
- "desc": "The griffon flies up to their speed without provoking opportunity attacks.\
    \ If the griffon has a creature [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled),\
    \ the grapple doesn't halve the griffon's speed and the griffon can end the grapple\
    \ at any point during this movement. If the griffon ends the grapple before the\
    \ end of their turn and the target takes bludgeoning damage from that fall, the\
    \ target takes an extra PB bludgeoning damage."
  "name": "3rd Level: Bombs Away (5 Ferocity)"
- "desc": "The griffon flies up to their speed without provoking opportunity attacks.\
    \ When the griffon ends this movement, each creature within 15 feet of them must\
    \ make a DC 10 plus PB Strength saving throw. On a failed save, a creature takes\
    \ PBd6 bludgeoning damage and is knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone).\
    \ On a successful save, a creature takes half as much damage and isn't knocked\
    \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "5th Level: Backdraft (8 Ferocity)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Griffon.png"
```
^statblock