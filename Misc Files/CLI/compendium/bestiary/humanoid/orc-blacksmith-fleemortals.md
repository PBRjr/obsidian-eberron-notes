---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/orc
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
aliases: ["Orc Blacksmith"]
---
# [Orc Blacksmith](Misc Files\CLI\compendium\bestiary\humanoid/orc-blacksmith-fleemortals.md)
*Source: Flee, Mortals! p. 214*  

```statblock
"name": "Orc Blacksmith (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "12"
- !!int "12"
"speed": "35 ft."
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
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "Common, Orc"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d10 plus PB bludgeoning damage. Beginning at 7th level, the blacksmith can\
    \ make this attack twice, instead of once, when they take the Attack action on\
    \ their turn."
  "name": "Signature Attack (Warhammer)"
- "desc": "When the blacksmith isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they take damage but aren't killed outright, they can make an attack against\
    \ an enemy (no action required) before the hit point reduction is resolved. If\
    \ the attack hits, the blacksmith regains twice their PB hit points."
  "name": "3rd Level: Relentless Rush (3/Day)"
- "desc": "As a bonus action, the blacksmith touches a piece of armor and fortifies\
    \ it. For the next 10 minutes, a creature wearing the armor gains a bonus to their\
    \ AC equal to half the blacksmith's PB."
  "name": "5th Level: Reinforce Armor (3/Day)"
- "desc": "As a bonus action, the blacksmith touches a weapon and polishes it. For\
    \ 1 minute, the weapon is magical and deals an extra PB damage."
  "name": "7th Level: Fortify Weapon (3/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Orc%20Blacksmith.png"
```
^statblock