---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
aliases: ["Goblin Lackey"]
---
# [Goblin Lackey](Misc Files\CLI\compendium\bestiary\humanoid/goblin-lackey-fleemortals.md)
*Source: Flee, Mortals! p. 127*  

```statblock
"name": "Goblin Lackey (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Minion"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](Misc%20Files/CLI/compendium/items/leather-armor-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "6"
"stats":
- !!int "8"
- !!int "13"
- !!int "10"
- !!int "10"
- !!int "8"
- !!int "8"
"speed": "30 ft., climb 20 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1/4"
"traits":
- "desc": "The lackey doesn't provoke opportunity attacks when they move out of an\
    \ enemy's reach."
  "name": "Crafty"
- "desc": "If the lackey takes damage from an attack or as the result of a failed\
    \ saving throw, their hit points are reduced to 0. If the lackey takes damage\
    \ from another effect, they die if the damage equals or exceeds their hit point\
    \ maximum; otherwise they take no damage."
  "name": "Minion"
- "desc": "If an enemy starts their turn within 5 feet of three or more lackeys who\
    \ can see them, the enemy must succeed on a Dexterity saving throw or take 1 piercing\
    \ damage for each lackey within 5 feet. The DC for this saving throw equals 10\
    \ + the number of lackeys within 5 feet of the enemy."
  "name": "Tiny Stabs"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, range 20/60 ft., one target.\
    \ Hit: 1 piercing damage."
  "name": "Dagger (Group Attack)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/main/img/FleeMortals/monsterToken/Goblin%20Lackey.webp"
```
^statblock