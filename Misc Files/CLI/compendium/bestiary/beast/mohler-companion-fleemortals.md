---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast/companion
statblock: inline
aliases: ["Mohler Companion"]
---
# [Mohler Companion](Misc Files\CLI\compendium\bestiary\beast/mohler-companion-fleemortals.md)
*Source: Flee, Mortals! p. 215*  

```statblock
"name": "Mohler Companion (FleeMortals)"
"size": "Small"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "7"
- !!int "16"
- !!int "14"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "20 ft., burrow 40 ft."
"saves":
  "Dexterity": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Stealth": !!int "0"
  "Acrobatics": !!int "0"
"senses": "blindsight 20 ft., tremorsense 40 ft., passive Perception 11"
"languages": ""
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB slashing damage."
  "name": "Signature Attack (Claw)"
- "desc": "The mohler burrows up to their speed and chooses one Large or smaller creature\
    \ they come within 5 feet of during the move. The target must succeed on a DC\
    \ 10 plus PB Dexterity saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "1st Level: Earth Bump (2 Ferocity)"
- "desc": "The mohler burrows up to their speed and targets a creature they can sense\
    \ on the surface within 10 feet of them. The target must succeed on a DC 10 plus\
    \ PB Strength saving throw or be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ by the ground until the start of the mohler's next turn."
  "name": "3rd Level: Sinkhole (5 Ferocity)"
- "desc": "Each creature on the ground within 10 feet of the mohler must succeed on\
    \ a DC 10 plus PB Strength saving throw or take 1d6 plus PB bludgeoning damage\
    \ and be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone). A creature\
    \ who fails this saving throw by 5 or more is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ by the ground (save ends at end of turn). A creature can use their action to\
    \ free themself or another creature within their reach, ending the effect."
  "name": "5th Level: Terranova (8 Ferocity)"
"reactions":
- "desc": "If the mohler's caregiver fails a Dexterity saving throw while they are\
    \ within 10 feet of the mohler and the mohler isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained), the mohler\
    \ pulls the caregiver out of danger. The caregiver succeeds on the saving throw\
    \ instead."
  "name": "Quick Pit (Recharges after a Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Mohler%20Companion.png"
```
^statblock