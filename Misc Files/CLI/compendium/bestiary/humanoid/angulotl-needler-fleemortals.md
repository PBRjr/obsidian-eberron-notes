---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/angulotl
- ttrpg-cli/monster/type/humanoid/artillery
statblock: inline
aliases: ["Angulotl Needler"]
---
# [Angulotl Needler](Misc Files\CLI\compendium\bestiary\humanoid/angulotl-needler-fleemortals.md)
*Source: Flee, Mortals! p. 29*  

```statblock
"name": "Angulotl Needler (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "angulotl, Artillery"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "54"
"hit_dice": "12d6 + 12"
"stats":
- !!int "7"
- !!int "18"
- !!int "12"
- !!int "11"
- !!int "16"
- !!int "8"
"speed": "20 ft., climb 20 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "6"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "5"
  "Acrobatics": !!int "6"
  "Survival": !!int "5"
"damage_immunities": "poison"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Angulotl"
"cr": "4"
"traits":
- "desc": "The needler can breathe air and water."
  "name": "Amphibious"
- "desc": "If the needler misses with a ranged weapon attack while they are hidden,\
    \ they remain hidden. Additionally, if the needler makes a ranged weapon attack\
    \ with advantage and hits, the attack deals an extra 3 (1d6) damage."
  "name": "Sniper"
- "desc": "When a creature hits the needler with a melee attack while within 5 feet\
    \ of them or touches the needler, that creature takes 2 (1d4) poison damage."
  "name": "Toxiferous"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage plus 7 (2d6) poison damage."
  "name": "Poison Shortsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 25/100 ft., one target. Hit:\
    \ 1 piercing damage, and the target must succeed on a DC 15 Constitution saving\
    \ throw or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) for 1\
    \ minute (save ends at end of turn). While [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ in this way, the target takes 14 (4d6) poison damage at the start of each\
    \ of their turns."
  "name": "Blowgun"
"bonus_actions":
- "desc": "The needler jumps a number of feet up to their walking speed, then takes\
    \ the Hide action."
  "name": "Hop and Hide"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Angulotl%20Needler.png"
```
^statblock