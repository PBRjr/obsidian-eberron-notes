---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/kobold
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
aliases: ["Kobold Decanus"]
---
# [Kobold Decanus](Misc Files\CLI\compendium\bestiary\humanoid/kobold-decanus-fleemortals.md)
*Source: Flee, Mortals! p. 179*  

```statblock
"name": "Kobold Decanus (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "12"
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
  "Perception": !!int "0"
  "History": !!int "0"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "Common, Draconic"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d8 plus PB piercing damage. Beginning at 7th level, the decanus can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Gladius)"
- "desc": "When the decanus sees an ally within 30 feet of them being targeted by\
    \ an attack, the decanus can use a reaction to move up to their speed toward the\
    \ target. If the decanus ends their movement within 5 feet of the target, the\
    \ target gains a +PB bonus to their AC until the beginning of the decanus's next\
    \ turn, including against the triggering attack."
  "name": "3rd Level: Reinforce (3/Day)"
- "desc": "The decanus attempts to topple a Medium or smaller creature within 5 feet\
    \ of them. The target must succeed on a DC 10 plus PB Strength saving throw or\
    \ be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone). Succeed or fail,\
    \ the decanus then makes two signature attacks against any creature within reach."
  "name": "5th Level: Shield Bash (3/Day)"
- "desc": "The decanus moves up to their speed, then makes a number of signature attacks\
    \ equal to the number of enemies within 5 feet of them (minimum of three attacks).\
    \ Each enemy within range must be attacked at least once. On a hit, the target\
    \ must succeed on a DC 10 plus PB Charisma saving throw or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of the decanus for 1 minute (save ends at end of turn)."
  "name": "7th Level: One-Kobold Army (1/Day)"
"source":
- "FleeMortals"
```
^statblock