---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/support
statblock: inline
aliases: ["Ceemal"]
---
# [Ceemal](Misc Files\CLI\compendium\bestiary\npc/ceemal-fleemortals.md)
*Source: Flee, Mortals! p. 358*  

```statblock
"name": "Ceemal (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Support"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "10"
- !!int "18"
- !!int "14"
- !!int "16"
- !!int "18"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "5"
  "Constitution": !!int "4"
"skillsaves":
  "Medicine": !!int "6"
  "Nature": !!int "5"
  "Stealth": !!int "8"
  "Perception": !!int "6"
  "Survival": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "Ceemal can attempt to hide even when they are only lightly obscured by\
    \ foliage, heavy rain, falling snow, mist, or other natural phenomena."
  "name": "Octopodan Camouflage"
"actions":
- "desc": "Ceemal makes two Fillet Knife or two Acid Spit attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage. If the target is a creature, another Abomination within\
    \ 5 feet of the target regains hit points equal to half the damage dealt."
  "name": "Fillet Knife"
- "desc": "Ranged Weapon Attack: +6 to hit, range 20/40 ft., one target. Hit:\
    \ 8 (1d8 + 4) acid damage, and the target is [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ until the start of Ceemal's next turn."
  "name": "Acid Spit"
"bonus_actions":
- "desc": "Ceemal chooses an ally within 30 feet of them who can hear them. The ally\
    \ can use their reaction to move up to their speed toward Ceemal without provoking\
    \ opportunity attacks."
  "name": "To Me, Sweetie (3/Day)"
"reactions":
- "desc": "When another Abomination who Ceemal can see is reduced to 0 hit points\
    \ by an enemy within 60 feet of Ceemal, Ceemal releases a psychic wail. The enemy\
    \ must make a DC 14 Constitution saving throw, taking 7 (2d6) psychic damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Wail of Loss"
"source":
- "FleeMortals"
```
^statblock