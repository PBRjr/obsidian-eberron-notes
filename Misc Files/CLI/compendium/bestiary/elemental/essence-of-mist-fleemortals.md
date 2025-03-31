---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/air
- ttrpg-cli/monster/type/elemental/ambusher
- ttrpg-cli/monster/type/elemental/water
statblock: inline
aliases: ["Essence of Mist"]
---
# [Essence of Mist](Misc Files\CLI\compendium\bestiary\elemental/essence-of-mist-fleemortals.md)
*Source: Flee, Mortals! p. 91*  

```statblock
"name": "Essence of Mist (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "air, water, Ambusher"
"alignment": "Any alignment"
"ac": !!int "15"
"hp": !!int "165"
"hit_dice": "22d8 + 66"
"stats":
- !!int "14"
- !!int "20"
- !!int "17"
- !!int "12"
- !!int "12"
- !!int "16"
"speed": "40 ft., fly 20 ft. (hover)"
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "10"
"skillsaves":
  "Sleight of Hand": !!int "10"
  "Deception": !!int "8"
  "Stealth": !!int "10"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
  \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled), [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
  \ [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 11"
"languages": "Aquan, Auran, Common"
"cr": "13"
"traits":
- "desc": "The essence can enter an enemy's space and stop there, and they can move\
    \ through a space as narrow as 1 inch wide without squeezing."
  "name": "Flowing Form"
- "desc": "While within 10 feet of the essence, creatures who need to breathe can't\
    \ take reactions or speak."
  "name": "Gasping Aura"
"actions":
- "desc": "The essence makes two Breathless Rend attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) slashing damage plus 22 (4d10) psychic damage."
  "name": "Breathless Rend"
"bonus_actions":
- "desc": "The essence imbues the power of breath in themself or another Elemental\
    \ they can see within 30 feet of them, granting one of the following effects of\
    \ that Elemental's choice:\n\n- Hide in Breath. The Elemental tries to hide\
    \ inside the body of a creature within 10 feet of them who isn't a Construct,\
    \ an Elemental, an Ooze, or an Undead. The target must succeed on a DC 18 Constitution\
    \ saving throw or the Elemental retreats inside the target until the start of\
    \ the Elemental's next turn. While inside the target, the Elemental can't take\
    \ actions and has total cover against attacks and other effects outside the target.\
    \  \n- Toxic Breath. The Elemental exudes a noxious aura 10 feet in every\
    \ direction for 1 minute or until dispersed by a moderate or stronger wind. That\
    \ area is lightly obscured, and each creature who needs to breathe who starts\
    \ their turn in that area must succeed on a DC 16 Constitution saving throw or\
    \ be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) until the end of\
    \ their next turn.  "
  "name": "Convocation of Breath (2/Day)"
- "desc": "The essence becomes [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ then takes the Hide action. This invisibility ends if the essence makes an attack\
    \ or uses Convocation of Breath."
  "name": "Breathstealer's Shimmer (1/Day)"
"source":
- "FleeMortals"
```
^statblock