---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/companion
statblock: inline
aliases: ["Rotbeast Companion"]
---
# [Rotbeast Companion](Misc Files\CLI\compendium\bestiary\beast/rotbeast-companion-fleemortals.md)
*Source: Flee, Mortals! p. 304*  

```statblock
"name": "Rotbeast Companion (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "5"
- !!int "12"
- !!int "8"
"speed": "30 ft."
"saves":
  "Constitution": !!int "0"
"skillsaves":
  "Athletics": !!int "0"
  "Survival": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 11"
"languages": ""
"traits":
- "desc": "The rotbeast and their caregiver ignore mundane difficult terrain."
  "name": "Rotted Path"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB piercing damage."
  "name": "Signature Attack (Horns)"
- "desc": "The rotbeast makes a signature attack. On a hit, the attack deals an extra\
    \ PB piercing damage, and the area within 5 feet of the target becomes difficult\
    \ terrain for the rotbeast's enemies until the start of the rotbeast's next turn."
  "name": "1st Level: Tainting Attack (2 Ferocity)"
- "desc": "The rotbeast moves up to their speed without provoking opportunity attacks,\
    \ then makes a signature attack. On a hit, the attack deals an extra PB bludgeoning\
    \ damage, and the target must succeed on a DC 10 plus PB Constitution saving throw\
    \ or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) until the start\
    \ of the rotbeast's next turn."
  "name": "3rd Level: Rotting Hooves (5 Ferocity)"
- "desc": "The rotbeast moves up to their speed without provoking opportunity attacks,\
    \ tainting the ground beneath their hooves and making it mundane difficult terrain\
    \ for their enemies until the start of the rotbeast's next turn. During this move,\
    \ the rotbeast can move through the space of Large or smaller creatures as if\
    \ they were difficult terrain. When a creature enters tainted ground for the first\
    \ time on a turn or starts their turn there, they must make a DC 10 plus PB Constitution\
    \ saving throw, taking PBd8 poison damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "5th Level: Rotwake Charge (8 Ferocity)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Rotbeast%20Companion.png"
```
^statblock