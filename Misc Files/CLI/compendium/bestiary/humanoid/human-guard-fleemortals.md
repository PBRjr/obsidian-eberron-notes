---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
aliases: ["Human Guard"]
---
# [Human Guard](Misc Files\CLI\compendium\bestiary\humanoid/human-guard-fleemortals.md)
*Source: Flee, Mortals! p. 162*  

```statblock
"name": "Human Guard (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Minion"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain shirt](Misc%20Files/CLI/compendium/items/chain-shirt-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "5"
"stats":
- !!int "12"
- !!int "12"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "When the guard makes or joins an attack that's made with advantage, the\
    \ attack deals an extra 1 damage per guard who made or joined the attack."
  "name": "Exploit Weakness"
- "desc": "If the guard takes damage from an attack or as the result of a failed saving\
    \ throw, their hit points are reduced to 0. If the guard takes damage from another\
    \ effect, they die if the damage equals or exceeds their hit point maximum; otherwise\
    \ they take no damage."
  "name": "Minion"
- "desc": "If a Medium or smaller enemy starts their turn within 5 feet of three or\
    \ more guards who can see them, until the start of the enemy's next turn, the\
    \ enemy's speed is reduced by 5 feet for each guard within 5 feet of them. If\
    \ this reduces the enemy's walking speed to 0, they are [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ until the start of their next turn."
  "name": "Overwhelm"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 1 piercing damage."
  "name": "Spear (Group Attack)"
"source":
- "FleeMortals"
```
^statblock