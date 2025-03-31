---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/brute
statblock: inline
aliases: ["Mummy"]
---
# [Mummy](Misc Files\CLI\compendium\bestiary\undead/mummy-fleemortals.md)
*Source: Flee, Mortals! p. 265*  

```statblock
"name": "Mummy (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Brute"
"alignment": "typically  Lawful Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"stats":
- !!int "16"
- !!int "8"
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Religion": !!int "2"
  "History": !!int "2"
  "Arcana": !!int "2"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
  \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened),\
  \ [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft., passive Perception 12"
"languages": "the languages they knew in life"
"cr": "3"
"traits":
- "desc": "Whenever the mummy takes fire damage, they take an extra 5 (1d10) fire\
    \ damage."
  "name": "Flammable"
- "desc": "Whenever the mummy takes piercing or slashing damage, each creature within\
    \ 5 feet of them takes 4 (1d8) poison damage."
  "name": "Mummy Dust"
"actions":
- "desc": "The mummy makes two Desiccating Slam attacks and uses Guardian Curse."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage. Until the start of the mummy's next turn, the\
    \ target's speed is reduced by 10 feet and the target can't regain hit points."
  "name": "Desiccating Slam"
- "desc": "The mummy calls down a scourge on one creature they can see within 60 feet\
    \ of them. The target must succeed on a DC 13 Wisdom saving throw or be cursed.\
    \ While cursed in this way, whenever the target takes damage, they take an extra\
    \ 3 (1d6) necrotic damage that can't be reduced in any way. The curse lasts\
    \ until removed by a cure ailment power, a [remove curse](Misc%20Files/CLI/compendium/spells/remove-curse-xphb.md)\
    \ spell, or a similar supernatural effect. A target who succeeds on their saving\
    \ throw is immune to the Guardian Curse of all mummies for the next 24 hours."
  "name": "Guardian Curse"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Mummy.png"
```
^statblock