---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead/brute
statblock: inline
aliases: ["Flesh Mournling"]
---
# [Flesh Mournling](Misc Files\CLI\compendium\bestiary\undead/flesh-mournling-fleemortals.md)
*Source: Flee, Mortals! p. 263*  

```statblock
"name": "Flesh Mournling (FleeMortals)"
"size": "Large"
"type": "undead"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "18"
- !!int "12"
- !!int "18"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "7"
"skillsaves":
  "Athletics": !!int "7"
  "Perception": !!int "4"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "understands the languages of their creator but can't speak"
"cr": "5"
"traits":
- "desc": "When an enemy who can hear the mournling starts their turn within 30 feet\
    \ of the mournling, the enemy must succeed on a DC 15 Wisdom saving throw or be\
    \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened) of the mournling\
    \ until the start of their next turn. A creature who succeeds on their saving\
    \ throw is immune to the Horrid Sob of all flesh mournlings for 24 hours."
  "name": "Horrid Sob"
- "desc": "The mournling is immune to any power, spell, or effect that would alter\
    \ their form."
  "name": "Immutable Form"
"actions":
- "desc": "The mournling makes two Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14\
    \ (3d6 + 4) bludgeoning damage. If the target is [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of the mournling, the target falls [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Slam"
- "desc": "The flesh mournling screams with unbearable pain in a 30-foot cone. Each\
    \ creature in that area who can hear the mournling must make a DC 15 Constitution\
    \ saving throw. On a failed save, a creature's eyes water uncontrollably, they\
    \ take 16 (3d10) psychic damage, and they can't see anything more than 5 feet\
    \ away until the end of their next turn. On a successful save, a creature takes\
    \ half as much damage and suffers no other effect."
  "name": "Agonizing Wail (Recharge 5-6)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Flesh%20Mournling.png"
```
^statblock