---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/skirmisher
statblock: inline
aliases: ["Lacuna"]
---
# [Lacuna](Misc Files\CLI\compendium\bestiary\fiend/lacuna-fleemortals.md)
*Source: Flee, Mortals! p. 322*  

```statblock
"name": "Lacuna (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"stats":
- !!int "5"
- !!int "10"
- !!int "17"
- !!int "18"
- !!int "16"
- !!int "24"
"speed": "0 ft."
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "5"
  "Wisdom": !!int "8"
"skillsaves":
  "Deception": !!int "12"
  "Insight": !!int "8"
  "Arcana": !!int "9"
  "Persuasion": !!int "12"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled),\
  \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned), [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
  \ [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained), [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned)"
"senses": "truesight 60 ft., passive Perception 13"
"languages": "Abyssal, Common, Infernal"
"cr": "15"
"traits":
- "desc": "If the lacuna is subjected to an effect that allows them to make a saving\
    \ throw to take only half damage, they instead take no damage if they succeed\
    \ on the saving throw, and only half damage if they fail."
  "name": "Avoidance"
- "desc": "While the lacuna remains motionless, they are indistinguishable from a\
    \ normal statue."
  "name": "False Appearance"
- "desc": "The lacuna doesn't have a walking speed and can't benefit from any bonus\
    \ to their speed."
  "name": "Fiend Between"
- "desc": "The lacuna has advantage on saving throws against powers, spells, and other\
    \ supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "The lacuna makes three Grief-Eater attacks and uses Infuse Sadness, if\
    \ available."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +12 to hit, reach 5 ft. or range 20 ft.,\
    \ one creature. Hit: 29 (4d10 + 7) psychic damage, and the target's speed\
    \ is reduced by 10 feet until the end of their next turn."
  "name": "Grief-Eater"
- "desc": "Each enemy the lacuna can see within 30 feet of them must succeed on a\
    \ DC 20 Wisdom saving throw or be overwhelmed with grief for 1 minute (save ends\
    \ at end of turn). While a creature is overwhelmed, attacks against them are made\
    \ with advantage."
  "name": "Infuse Sadness (1/Day)"
"bonus_actions":
- "desc": "The lacuna teleports up to 60 feet to an unoccupied space they can see."
  "name": "Slip Between"
"reactions":
- "desc": "When a creature within 60 feet of the lacuna targets them with an attack,\
    \ the lacuna teleports up to 60 feet to an unoccupied space they can see. If the\
    \ lacuna is no longer a valid target for the triggering attack, the attacker must\
    \ choose a new target or the attack misses."
  "name": "Slip Away"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/main/img/FleeMortals/monsterToken/Lacuna.webp"
```
^statblock