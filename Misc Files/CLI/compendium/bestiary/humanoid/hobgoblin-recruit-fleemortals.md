---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
aliases: ["Hobgoblin Recruit"]
---
# [Hobgoblin Recruit](Misc Files\CLI\compendium\bestiary\humanoid/hobgoblin-recruit-fleemortals.md)
*Source: Flee, Mortals! p. 150*  

```statblock
"name": "Hobgoblin Recruit (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Minion"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](Misc%20Files/CLI/compendium/items/leather-armor-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "7"
"stats":
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "11"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin, Infernal"
"cr": "1/2"
"traits":
- "desc": "When a creature within 5 feet of the recruit reduces the recruit to 0 hit\
    \ points, the recruit's corpse unleashes a spray of burning orange ichor. The\
    \ creature who reduced the recruit to 0 hit points takes 1 fire damage."
  "name": "Infernal Ichor"
- "desc": "If the recruit takes damage from an attack or as the result of a failed\
    \ saving throw, their hit points are reduced to 0. If the recruit takes damage\
    \ from another effect, they die if the damage equals or exceeds their hit point\
    \ maximum; otherwise they take no damage."
  "name": "Minion"
- "desc": "When a non-minion ally attacks a creature, that ally gains a +1 bonus to\
    \ the attack roll for each recruit within 5 feet of the target (maximum bonus\
    \ of +5)."
  "name": "Tactical Positioning"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1\
    \ slashing damage."
  "name": "Longsword (Group Attack)"
"source":
- "FleeMortals"
```
^statblock