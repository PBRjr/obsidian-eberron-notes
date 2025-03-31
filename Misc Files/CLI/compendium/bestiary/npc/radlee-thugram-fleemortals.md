---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
aliases: ["Radlee Thugram"]
---
# [Radlee Thugram](Misc Files\CLI\compendium\bestiary\npc/radlee-thugram-fleemortals.md)
*Source: Flee, Mortals! p. 384*  

```statblock
"name": "Radlee Thugram (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Soldier"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate](Misc%20Files/CLI/compendium/items/plate-armor-xphb.md)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"stats":
- !!int "24"
- !!int "16"
- !!int "15"
- !!int "11"
- !!int "16"
- !!int "12"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Strength": !!int "10"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "10"
  "Perception": !!int "6"
  "Survival": !!int "6"
"senses": "truesight 60 ft., passive Perception 16"
"languages": "Common"
"cr": "7"
"traits":
- "desc": "When Radlee makes an attack, she has advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
- "desc": "Radlee has advantage on saving throws against being moved against her will\
    \ or knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Sure-Footed"
- "desc": "Radlee has advantage on initiative checks.\n\nWhile she isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ Radlee and each ally within 30 feet of her who can see or hear her can't be\
    \ surprised."
  "name": "Tactical Vigilance"
"actions":
- "desc": "Radlee makes three Halberd or three Longbow attacks. Alternatively, she\
    \ makes one Halberd attack and uses Backswipe."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 12\
    \ (1d10 + 7) slashing damage."
  "name": "Halberd"
- "desc": "Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage."
  "name": "Longbow"
- "desc": "Radlee swings her halberd's shaft at a creature within 5 feet of her. The\
    \ target must succeed on a DC 18 Strength saving throw or take 16 (3d10) bludgeoning\
    \ damage and be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Backswipe"
"reactions":
- "desc": "When a creature Radlee can see within 10 feet of her attacks one of her\
    \ allies, Radlee can make a Halberd attack against the attacker."
  "name": "Protector"
"source":
- "FleeMortals"
```
^statblock