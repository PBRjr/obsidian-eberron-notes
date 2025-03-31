---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/beast/ambusher
statblock: inline
aliases: ["Wildcat"]
---
# [Wildcat](Misc Files\CLI\compendium\bestiary\beast/wildcat-fleemortals.md)
*Source: Flee, Mortals! p. 43*  

```statblock
"name": "Wildcat (FleeMortals)"
"size": "Unknown"
"type": "beast"
"subtype": "Ambusher"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "37"
"hit_dice": "5d10 + 10"
"stats":
- !!int "17"
- !!int "15"
- !!int "14"
- !!int "6"
- !!int "14"
- !!int "8"
"speed": "60 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "1"
"traits":
- "desc": "If the wildcat hits a Large or smaller target and had advantage on the\
    \ attack roll, the target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 13). While grappling the target in this way, the wildcat can't attack\
    \ another creature."
  "name": "Hunter's Pounce"
- "desc": "The wildcat has advantage on Dexterity ([Stealth](Misc%20Files/CLI/rules/skills.md#Stealth))\
    \ checks made in their native terrain."
  "name": "Natural Camouflage"
- "desc": "When the wildcat moves on their turn in combat, they can triple their speed\
    \ until the end of their turn."
  "name": "Sprint (Recharges after a Short or Long Rest)"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage, plus an extra 3 (1d6) piercing damage if the target\
    \ is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, plus an extra 3 (1d6) slashing damage if the wildcat\
    \ had advantage on the attack roll."
  "name": "Claw"
"bonus_actions":
- "desc": "The wildcat takes the Hide action."
  "name": "Sneak"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Wildcat.png"
```
^statblock