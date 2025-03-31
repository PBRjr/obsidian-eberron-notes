---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/fire
- ttrpg-cli/monster/type/elemental/retainer
statblock: inline
aliases: ["Lava Bastion"]
---
# [Lava Bastion](Misc Files\CLI\compendium\bestiary\elemental/lava-bastion-fleemortals.md)
*Source: Flee, Mortals! p. 102*  

```statblock
"name": "Lava Bastion (FleeMortals)"
"size": "Large"
"type": "elemental"
"subtype": "earth, fire, Retainer"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "heavy armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "12"
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
  "Insight": !!int "0"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., tremorsense 10 ft., passive Perception 11"
"languages": "Common, Dwarvish, Ignan, Terran"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 + PB bludgeoning damage plus 4 (1d8) fire damage. A flammable object\
    \ hit by this attack ignites if it isn't being worn or carried. Beginning at 7th\
    \ level, the bastion can make this attack twice, instead of once, when they take\
    \ the Attack action on their turn."
  "name": "Signature Attack (Molten Slam)"
- "desc": "As an action, the bastion makes a signature attack against a creature within\
    \ range. If the attack hits, the target is also [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). While [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, a target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and takes PBd6 fire damage at the start of each of their turns."
  "name": "3rd Level: Burning Embrace (3/Day)"
- "desc": "When the bastion hits a creature with a signature attack, the creature\
    \ takes an extra PBd4 fire damage. If the target is wielding a mundane metal\
    \ weapon, the bastion partially melts the target's weapon, giving it a permanent\
    \ -2 penalty to attack and damage rolls. If the target is wielding a supernatural\
    \ metal weapon, the penalty lasts for 1 hour instead."
  "name": "5th Level: Melting Grasp (3/Day)"
- "desc": "As an action, the bastion erupts, shooting a 30-foot cone of earth and\
    \ lava from their head. Each creature in that area must make a DC 10 plus PB Dexterity\
    \ saving throw. On a failed save, a target takes PBd6 bludgeoning damage plus\
    \ PBd6 fire damage and is knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone).\
    \ On a successful save, a target takes half as much damage and is not knocked\
    \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone). The lava spreads around\
    \ corners and ignites flammable objects in that area that aren't being worn or\
    \ carried."
  "name": "7th Level: Eruption (1/Day)"
"source":
- "FleeMortals"
```
^statblock