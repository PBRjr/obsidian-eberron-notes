---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/gnoll
- ttrpg-cli/monster/type/fiend/retainer
statblock: inline
aliases: ["Gnoll Gnasher"]
---
# [Gnoll Gnasher](Misc Files\CLI\compendium\bestiary\fiend/gnoll-gnasher-fleemortals.md)
*Source: Flee, Mortals! p. 123*  

```statblock
"name": "Gnoll Gnasher (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "16"
- !!int "12"
- !!int "12"
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
  "Intimidation": !!int "0"
  "Athletics": !!int "0"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Common, Gnoll"
"actions":
- "desc": "Melee Weapon Attack: +3 plus damage. Beginning at 7th level, the gnasher\
    \ can make this attack twice, instead of once, when they take the Attack action\
    \ on their turn."
  "name": "Signature Attack (Bite)"
- "desc": "When a creature the gnasher can see within 30 feet of them is reduced to\
    \ 0 hit points, the gnasher can use a reaction to move up to half their speed\
    \ and then make a signature attack. On a hit, the attack deals an extra PB piercing\
    \ damage."
  "name": "3rd Level: Frenzied Bite (3/Day)"
- "desc": "As an action, the gnasher makes a signature attack against up to PB creatures\
    \ within 5 feet of them."
  "name": "5th Level: Flurry of Fangs (3/Day)"
- "desc": "When the gnasher reduces a creature to 0 hit points with their signature\
    \ attack, they can consume part of the creature as part of the attack, gaining\
    \ PBd10 temporary hit points. Each enemy within 30 feet of the gnasher who can\
    \ see them must succeed on a DC 10 plus PB Wisdom saving throw or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of the gnasher until the end of the gnasher's next turn."
  "name": "7th Level: Horrific Feast (1/Day)"
"source":
- "FleeMortals"
```
^statblock