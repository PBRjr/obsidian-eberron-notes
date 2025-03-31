---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/minotaur
- ttrpg-cli/monster/type/monstrosity/retainer
statblock: inline
aliases: ["Minotaur Devastator"]
---
# [Minotaur Devastator](Misc Files\CLI\compendium\bestiary\monstrosity/minotaur-devastator-fleemortals.md)
*Source: Flee, Mortals! p. 197*  

```statblock
"name": "Minotaur Devastator (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "minotaur, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Athletics": !!int "0"
  "Survival": !!int "0"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d10 plus PB piercing damage. Beginning at 7th level, the devastator can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Goring Horns)"
- "desc": "As an action, the devastator moves up to their speed. At the end of this\
    \ movement, they can make a signature attack. If that attack hits a Large or smaller\
    \ creature, the target is pushed up to 10 feet away from the devastator, and the\
    \ devastator and their allies have advantage on attack rolls against the target\
    \ until the end of the devastator's next turn."
  "name": "3rd Level: Furious Charge (3/Day)"
- "desc": "As an action, the devastator makes a signature attack against a creature\
    \ within 5 feet of them. On a hit, the attack deals an extra PBd10 piercing\
    \ damage, and the target must succeed on a DC 10 plus PB Wisdom saving throw or\
    \ be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened) of the devastator\
    \ until the end of the devastator's next turn."
  "name": "5th Level: Fearsome Gore (3/Day)"
- "desc": "When a creature the devastator can see within 40 feet of them deals damage\
    \ to the devastator, the devastator can use a reaction to move up to their speed\
    \ toward the creature. If the devastator ends this movement within 5 feet of the\
    \ creature, they can make two signature attacks against the creature with a +PB\
    \ bonus to those attack and damage rolls."
  "name": "7th Level: Retaliatory Charge (1/Day)"
"source":
- "FleeMortals"
```
^statblock