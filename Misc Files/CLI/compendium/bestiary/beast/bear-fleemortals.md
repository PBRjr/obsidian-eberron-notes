---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/controller
statblock: inline
aliases: ["Bear"]
---
# [Bear](Misc Files\CLI\compendium\bestiary\beast/bear-fleemortals.md)
*Source: Flee, Mortals! p. 35*  

```statblock
"name": "Bear (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"stats":
- !!int "19"
- !!int "10"
- !!int "17"
- !!int "8"
- !!int "12"
- !!int "7"
"speed": "40 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "3"
  "Survival": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "The bear has a +10 bonus to Wisdom ([Perception](Misc%20Files/CLI/rules/skills.md#Perception))\
    \ checks that rely on smell, and they can smell creatures even through dirt, snow,\
    \ and water."
  "name": "Exceptional Smell"
- "desc": "The bear has advantage on Dexterity ([Stealth](Misc%20Files/CLI/rules/skills.md#Stealth))\
    \ checks made in their native terrain."
  "name": "Natural Camouflage"
"actions":
- "desc": "The bear makes one Bite attack and one Claw attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage. If the target is Medium or smaller, they are [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 14). Until this grapple ends, the bear can't use their Bite attack\
    \ on another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 4) slashing damage. If the target is Medium or smaller, they are knocked\
    \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d12 + 4) bludgeoning damage. If the target is Medium or smaller, they are\
    \ shoved up to 10 feet away and knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone).\
    \ If the target hits a solid surface, they take an extra 7 (2d6) bludgeoning\
    \ damage."
  "name": "Powerful Swipe (Recharge 6)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Bear.png"
```
^statblock