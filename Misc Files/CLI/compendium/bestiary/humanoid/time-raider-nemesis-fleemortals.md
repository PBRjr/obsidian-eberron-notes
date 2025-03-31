---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/skirmisher
- ttrpg-cli/monster/type/humanoid/time-raider
statblock: inline
aliases: ["Time Raider Nemesis"]
---
# [Time Raider Nemesis](Misc Files\CLI\compendium\bestiary\humanoid/time-raider-nemesis-fleemortals.md)
*Source: Flee, Mortals! p. 231*  

```statblock
"name": "Time Raider Nemesis (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "time raider, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "precog reflexes"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"stats":
- !!int "18"
- !!int "16"
- !!int "14"
- !!int "18"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"saves":
  "Intelligence": !!int "7"
  "Strength": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "6"
  "Athletics": !!int "7"
  "Stealth": !!int "6"
  "Perception": !!int "4"
  "Arcana": !!int "7"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
  \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Common, Kuran'zoi, telepathy 60 ft."
"cr": "8"
"traits":
- "desc": "The nemesis adds their Intelligence modifier (+4) to initiative rolls and\
    \ to their AC (included in Armor Class)."
  "name": "Precog Reflexes"
- "desc": "The nemesis is immune to any effect that would sense their emotions, read\
    \ their thoughts, reveal they are lying, or reveal their alignment or location."
  "name": "Psychic Scar"
"actions":
- "desc": "The nemesis makes two Golden Scythe attacks. They can replace one attack\
    \ with a use of Kinetic Crush or Phase, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage plus 13 (3d8) necrotic damage. If this attack\
    \ reduces a creature who is in an astral body (as with the [astral projection](Misc%20Files/CLI/compendium/spells/astral-projection-xphb.md)\
    \ spell) to 0 hit points, that creature's soul returns to their material body,\
    \ and then their material body is also reduced to 0 hit points."
  "name": "Golden Scythe"
- "desc": "The nemesis attempts to telekinetically grip one creature they can see\
    \ within 60 feet of them. The target must make a DC 15 Strength saving throw.\
    \ On a failed save, the target takes 27 (6d8) force damage, and their speed\
    \ becomes 0 until the start of the nemesis's next turn. On a successful save,\
    \ a target takes half as much damage and their speed isn't reduced."
  "name": "Kinetic Crush (4th-Order Power)"
- "desc": "For 1 minute, the nemesis can move through other creatures and objects\
    \ as if they were difficult terrain. The nemesis takes 5 (1d10) force damage\
    \ if they end their turn inside an object. If this power ends while the nemesis\
    \ is inside an object, they are shunted out of the object into the nearest unoccupied\
    \ space of their choice."
  "name": "Phase (1/Day; 4th-Order Power; Concentration)"
"bonus_actions":
- "desc": "The nemesis teleports up to 30 feet to an unoccupied space they can see."
  "name": "Jaunt (3/Day; 3rd-Order Power)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Time%20Raider%20Nemesis.png"
```
^statblock