---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon/controller
statblock: inline
aliases: ["Wyvern"]
---
# [Wyvern](Misc Files\CLI\compendium\bestiary\dragon/wyvern-fleemortals.md)
*Source: Flee, Mortals! p. 290*  

```statblock
"name": "Wyvern (FleeMortals)"
"size": "Large"
"type": "dragon"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"stats":
- !!int "17"
- !!int "12"
- !!int "16"
- !!int "4"
- !!int "14"
- !!int "6"
"speed": "20 ft., fly 60 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Perception": !!int "5"
"damage_immunities": "acid"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "6"
"traits":
- "desc": "The wyvern is immune to the [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ and [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned) conditions while\
    \ they have fewer than half their hit points or are within 60 feet of another\
    \ wyvern they can hear or see."
  "name": "Stubborn Rage"
"actions":
- "desc": "The wyvern makes one Stinger attack and one Bite attack. They can replace\
    \ one attack with a use of Tail Sweep."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 15 ft., one target. Hit: 13\
    \ (3d6 + 3) piercing damage. The target must succeed on a DC 14 Constitution\
    \ saving throw or take 7 (2d6) acid damage at the start of each of their turns\
    \ for 1 minute (save ends at end of turn). A cure ailment power or a [lesser restoration](Misc%20Files/CLI/compendium/spells/lesser-restoration-xphb.md)\
    \ spell ends this effect on a target."
  "name": "Stinger"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d12 + 3) piercing damage. If the target is Large or smaller, they are [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 13). Until this grapple ends, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and the wyvern can't bite another target."
  "name": "Bite"
- "desc": "The wyvern swipes their tail in a 15-foot cone. Each creature in that area\
    \ must succeed on a DC 14 Strength saving throw or take 14 (2d10 + 3) bludgeoning\
    \ damage and be pushed up to 10 feet away from the wyvern."
  "name": "Tail Sweep"
"bonus_actions":
- "desc": "The wyvern takes the Search action."
  "name": "Seek"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Wyvern.png"
```
^statblock