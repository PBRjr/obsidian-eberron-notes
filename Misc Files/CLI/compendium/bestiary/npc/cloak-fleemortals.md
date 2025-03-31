---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
aliases: ["Cloak"]
---
# [Cloak](Misc Files\CLI\compendium\bestiary\npc/cloak-fleemortals.md)
*Source: Flee, Mortals! p. 364*  

```statblock
"name": "Cloak (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Ambusher"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "10"
- !!int "20"
- !!int "14"
- !!int "15"
- !!int "12"
- !!int "15"
"speed": "40 ft."
"saves":
  "Charisma": !!int "4"
  "Dexterity": !!int "7"
  "Constitution": !!int "4"
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "9"
  "Insight": !!int "3"
  "Perception": !!int "3"
  "Acrobatics": !!int "7"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "4"
"traits":
- "desc": "When Cloak makes an attack, she has advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
"actions":
- "desc": "Cloak makes two Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6\
    \ + 5) piercing damage plus 3 (1d6) poison damage, and the target is [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ until the start of Cloak's next turn."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. Hit:\
    \ 8 (1d8 + 5) piercing damage. If the target is a creature who hasn't moved\
    \ since the end of Cloak's last turn, the attack deals an extra 7 (2d6) piercing\
    \ damage."
  "name": "Light Crossbow"
- "desc": "If not in the Cyst, Cloak teleports to the Cyst. If in the Cyst, she teleports\
    \ to a place she has visited."
  "name": "Iron Ring (2/Day)"
"bonus_actions":
- "desc": "Cloak takes the Dash, Disengage, or Hide action."
  "name": "Cunning Action"
"reactions":
- "desc": "If a creature within 5 feet of Cloak hits one of her allies with an attack,\
    \ Cloak makes a Shortsword attack against the creature. To use this reaction,\
    \ Cloak must be able to see the ally and the attacker."
  "name": "You Should've Been Watching Me"
"source":
- "FleeMortals"
```
^statblock