---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
aliases: ["Canon Athenodorus"]
---
# [Canon Athenodorus](Misc Files\CLI\compendium\bestiary\humanoid/canon-athenodorus-fleemortals.md)
*Source: Flee, Mortals! p. 364*  

```statblock
"name": "Canon Athenodorus (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Controller"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](Misc%20Files/CLI/compendium/items/plate-armor-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "20"
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "20"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "3"
  "Wisdom": !!int "7"
  "Constitution": !!int "4"
"skillsaves":
  "Athletics": !!int "7"
  "Deception": !!int "3"
  "Religion": !!int "4"
  "Insight": !!int "7"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "In addition to any other spells in this stat block, Athenodorus can cast\
    \ the following spells, using Wisdom as the spellcasting ability (spell save DC\
    \ 15):\n\nAt will: [light](Misc%20Files/CLI/compendium/spells/light-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [mending](Misc%20Files/CLI/compendium/spells/mending-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n1/day each: [divination](Misc%20Files/CLI/compendium/spells/divination-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [glyph of warding](Misc%20Files/CLI/compendium/spells/glyph-of-warding-xphb.md)\
    \ <sup>[+](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time |\n\
    |-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action |\n| R\
    \ | 1 reaction |\n| + | Longer than 1 action (see spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "When Athenodorus makes an attack, he has advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) bludgeoning damage. If the target is a creature, they are hexed\
    \ until the end of their next turn. Whenever a creature hexed in this way makes\
    \ an attack roll or saving throw, they must roll a d4 and subtract the number\
    \ rolled from the attack roll or saving throw."
  "name": "Star of Iron"
- "desc": "If not in the Cyst, Athenodorus teleports to the Cyst. If in the Cyst,\
    \ he teleports to a place he has visited."
  "name": "Iron Ring (2/Day)"
- "desc": "Athenodorus calls unholy black flames from the depths at a point he can\
    \ see within 90 feet of him. Each enemy in a 15-foot-radius, 30-foot-high cylinder\
    \ centered on that point must make a DC 15 Dexterity saving throw. On a failed\
    \ save, a creature takes 14 (4d6) fire damage plus 14 (4d6) necrotic damage\
    \ and is moved up to 15 feet horizontally. On a successful save, a creature takes\
    \ half as much damage and isn't moved."
  "name": "Unholy Fire (2/Day; 3rd-Level Spell)"
"bonus_actions":
- "desc": "Athenodorus chooses a creature he can see within 30 feet of him. The target\
    \ regains 14 (2d8 + 5) hit points and Athenodorus can end one of the following\
    \ conditions affecting the target: [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned),\
    \ or [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned)."
  "name": "Blessing of Ajax (2/Day)"
"source":
- "FleeMortals"
```
^statblock