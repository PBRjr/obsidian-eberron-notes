---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/ambusher
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Grilp"]
---
# [Grilp](Misc Files\CLI\compendium\bestiary\fiend/grilp-fleemortals.md)
*Source: Flee, Mortals! p. 154*  

```statblock
"name": "Grilp (FleeMortals)"
"size": "Tiny"
"type": "fiend"
"subtype": "devil, Ambusher"
"alignment": "typically  Lawful Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d4 + 3"
"stats":
- !!int "6"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "12"
- !!int "11"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_immunities": "fire, necrotic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Goblin, Infernal"
"cr": "1/4"
"traits":
- "desc": "The grilp has advantage on Dexterity ([Stealth](Misc%20Files/CLI/rules/skills.md#Stealth))\
    \ checks and can hide from creatures who are observing them."
  "name": "Shifting Camouflage"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage, and if the target is a creature, they must succeed on\
    \ a DC 11 Constitution saving throw or gain vulnerability to fire and necrotic\
    \ damage until the start of the grilp's next turn."
  "name": "Bite"
- "desc": "Ranged Spell Attack: +3 to hit, range 30 ft., one target. Hit: 3\
    \ (1d6) necrotic damage."
  "name": "Necrotic Mote"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Grilp.png"
```
^statblock