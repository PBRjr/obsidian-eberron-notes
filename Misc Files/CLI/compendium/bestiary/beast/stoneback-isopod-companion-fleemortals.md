---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/companion
statblock: inline
aliases: ["Stoneback Isopod Companion"]
---
# [Stoneback Isopod Companion](Misc Files\CLI\compendium\bestiary\beast/stoneback-isopod-companion-fleemortals.md)
*Source: Flee, Mortals! p. 330*  

```statblock
"name": "Stoneback Isopod Companion (FleeMortals)"
"size": "Medium"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "15 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "5"
- !!int "10"
- !!int "8"
"speed": "30 ft., climb 20 ft., swim 20 ft."
"saves":
  "Constitution": !!int "0"
"skillsaves":
  "Stealth": !!int "0"
"damage_resistances": "cold, fire"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"traits":
- "desc": "The isopod can breathe air and water."
  "name": "Amphibious"
- "desc": "The isopod has advantage on Dexterity ([Stealth](Misc%20Files/CLI/rules/skills.md#Stealth))\
    \ checks made to hide in rocky terrain."
  "name": "Stone Camouflage"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB piercing damage."
  "name": "Signature Attack (Bite)"
- "desc": "The isopod makes a signature attack. On a hit, the target's speed is also\
    \ reduced by 10 feet until the end of the isopod's next turn."
  "name": "1st Level: Mangling Attack (2 Ferocity)"
- "desc": "The isopod moves up to their walking speed without provoking opportunity\
    \ attacks.\n\nWhile doing so, they can move through the spaces of Large or smaller\
    \ creatures as if they were difficult terrain. If the isopod enters another creature's\
    \ space during this move, that creature must succeed on a DC 10 plus PB Strength\
    \ saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "3rd Level: Push Through (5 Ferocity)"
- "desc": "The isopod moves up to their speed without provoking opportunity attacks\
    \ and makes a signature attack. On a hit, the target is also [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). While [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, the target is [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed)\
    \ and [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)."
  "name": "5th Level: Tackle (8 Ferocity)"
"reactions":
- "desc": "When the isopod's caregiver is hit with an attack while within 5 feet of\
    \ the isopod, the isopod curls around the caregiver, giving the caregiver a +PB\
    \ bonus to their AC against the attack."
  "name": "Emergency Hug (Recharges after a Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Stoneback%20Isopod%20Companion.png"
```
^statblock