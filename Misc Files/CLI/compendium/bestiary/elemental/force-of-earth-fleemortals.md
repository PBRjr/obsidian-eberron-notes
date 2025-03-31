---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/soldier
statblock: inline
aliases: ["Force of Earth"]
---
# [Force of Earth](Misc Files\CLI\compendium\bestiary\elemental/force-of-earth-fleemortals.md)
*Source: Flee, Mortals! p. 95*  

```statblock
"name": "Force of Earth (FleeMortals)"
"size": "Large"
"type": "elemental"
"subtype": "earth, Soldier"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "19"
- !!int "9"
- !!int "18"
- !!int "10"
- !!int "14"
- !!int "9"
"speed": "30 ft., burrow 20 ft."
"skillsaves":
  "Athletics": !!int "7"
  "History": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 12"
"languages": "Common, Terran"
"cr": "5"
"traits":
- "desc": "The force of earth can burrow through mundane, unworked earth and stone.\
    \ While doing so, the force of earth doesn't disturb the material they move through."
  "name": "Earth Glide"
"actions":
- "desc": "The force of earth makes two Earthbind Strike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage, and the target's speed becomes 0 until the start\
    \ of the force of earth's next turn."
  "name": "Earthbind Strike"
- "desc": "Ranged Weapon Attack: +7 to hit, range 60/120 ft., one target. Hit:\
    \ 23 (3d12 + 4) bludgeoning damage, or 47 (6d12 + 8) bludgeoning damage if\
    \ the target is an object or structure."
  "name": "Shatter Rock"
"bonus_actions":
- "desc": "The force of earth imbues the power of earth in themself or another Elemental\
    \ they can see within 30 feet of them, granting one of the following effects of\
    \ that Elemental's choice:\n\n- Earthen Aura. Stones rapidly whir around the\
    \ Elemental in a 10-foot-radius sphere for 1 minute or until they're killed or\
    \ [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated). A creature\
    \ who isn't an Elemental takes 5 slashing damage for every 5 feet they move into\
    \ or within that area.  \n- Stone Armor. Stone grows over the Elemental in\
    \ a protective carapace, and they gain 20 temporary hit points. While the Elemental\
    \ has these temporary hit points, they are immune to the [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
    \ and [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned) conditions.  "
  "name": "Convocation of Earth (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Force%20of%20Earth.png"
```
^statblock