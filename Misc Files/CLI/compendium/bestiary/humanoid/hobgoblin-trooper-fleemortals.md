---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
aliases: ["Hobgoblin Trooper"]
---
# [Hobgoblin Trooper](Misc Files\CLI\compendium\bestiary\humanoid/hobgoblin-trooper-fleemortals.md)
*Source: Flee, Mortals! p. 152*  

```statblock
"name": "Hobgoblin Trooper (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Soldier"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[ring mail](Misc%20Files/CLI/compendium/items/ring-mail-xphb.md), [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "18"
"hit_dice": "4d8"
"stats":
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "2"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin, Infernal"
"cr": "1/2"
"traits":
- "desc": "When the trooper dies, their corpse unleashes a spray of burning orange\
    \ ichor. Each creature within 5 feet of the trooper takes 2 fire damage."
  "name": "Infernal Ichor"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage, and another target within 5 feet of the first takes\
    \ 2 (1d4) fire damage."
  "name": "Fire Flail"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage plus 2 (1d4) fire damage."
  "name": "Brimstone Dagger"
"bonus_actions":
- "desc": "The trooper hexes a creature within 5 feet of them who isn't already hexed\
    \ by another trooper. The first time on a turn a hexed creature damages a creature\
    \ other than the trooper, the hexed creature takes 5 fire damage. The hex lasts\
    \ until the start of the trooper's next turn."
  "name": "Fight Me, Coward"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Hobgoblin%20Trooper.png"
```
^statblock