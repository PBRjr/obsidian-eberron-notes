---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/controller
statblock: inline
aliases: ["Koptourok"]
---
# [Koptourok](Misc Files\CLI\compendium\bestiary\undead/koptourok-fleemortals.md)
*Source: Flee, Mortals! p. 295*  

```statblock
"name": "Koptourok (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Controller"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"stats":
- !!int "9"
- !!int "16"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "8"
"speed": "30 ft. (see wings of breath)"
"saves":
  "Dexterity": !!int "6"
  "Constitution": !!int "6"
"skillsaves":
  "Perception": !!int "4"
"damage_resistances": "necrotic; poison; bludgeoning, piercing, slashing from mundane\
  \ attacks"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 14"
"languages": "understands the languages they knew in life but can't speak"
"cr": "5"
"traits":
- "desc": "Enemies within 30 feet of the koptourok can't speak, and if they are a\
    \ creature who needs to breathe, they also have disadvantage on Constitution saving\
    \ throws."
  "name": "Breathless Aura"
- "desc": "The koptourok gains a flying speed equal to their walking speed if they\
    \ have at least one enemy within 30 feet of them. If the koptourok starts their\
    \ turn in the air and doesn't have a flying speed, they fall."
  "name": "Wings of Breath"
"actions":
- "desc": "The koptourok makes two Choking Grasp attacks."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +6 to hit, reach 30 ft., one creature. Hit: 14\
    \ (4d6) bludgeoning damage, and the target is pulled to an unoccupied space\
    \ within 5 feet of the koptourok and [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 14). While [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and the koptourok's speed isn't halved by the grapple."
  "name": "Choking Grasp"
- "desc": "The koptourok attempts to steal the breath from each creature they are\
    \ grappling. Each target must make a DC 14 Constitution saving throw, taking 14\
    \ (4d6) bludgeoning damage on a failed save, or half as much damage on a successful\
    \ one. The koptourok gains temporary hit points equal to 5 times the number of\
    \ creatures who failed their save."
  "name": "Last Gasp"
"reactions":
- "desc": "When the koptourok drops to 30 hit points or fewer, they unleash a shrieking\
    \ wail. Each creature within 30 feet of the koptourok must make a DC 14 Constitution\
    \ saving throw. On a failed save, a creature takes 16 (3d10) thunder damage\
    \ and is [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened) until the end\
    \ of their next turn. On a successful save, a creature takes half as much damage\
    \ and isn't [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened). The koptourok\
    \ then releases all creatures they are grappling and flies up to their speed."
  "name": "Thunderous Deflation"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Koptourok.png"
```
^statblock