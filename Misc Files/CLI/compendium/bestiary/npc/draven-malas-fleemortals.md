---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
aliases: ["Draven Malas"]
---
# [Draven Malas](Misc Files\CLI\compendium\bestiary\npc/draven-malas-fleemortals.md)
*Source: Flee, Mortals! p. 390*  

```statblock
"name": "Draven Malas (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Controller"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"stats":
- !!int "10"
- !!int "26"
- !!int "18"
- !!int "26"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "11"
  "Intelligence": !!int "11"
  "Constitution": !!int "7"
"skillsaves":
  "Investigation": !!int "11"
  "Arcana": !!int "11"
"damage_resistances": "acid, necrotic"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 10"
"languages": "Common, Draconic"
"cr": "7"
"traits":
- "desc": "In addition to any other spells in this stat block, Draven can cast the\
    \ following spells, using Intelligence as the spellcasting ability (spell save\
    \ DC 19):\n\nAt will: [alarm](Misc%20Files/CLI/compendium/spells/alarm-xphb.md)\
    \ <sup>[+](#^superscript-casting-time)</sup>, [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n1/day each: [glyph of warding](Misc%20Files/CLI/compendium/spells/glyph-of-warding-xphb.md)\
    \ <sup>[+](#^superscript-casting-time)</sup>, [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md)\
    \ <sup>[+](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time |\n\
    |-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action |\n| R\
    \ | 1 reaction |\n| + | Longer than 1 action (see spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "When Draven makes an attack, he has advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
- "desc": "When Draven hits a creature with a melee attack, he can sacrifice his vitality\
    \ to empower the attack. The target's speed drops to 0 until the start of his\
    \ next turn, and Draven takes 5 (1d10) psychic damage."
  "name": "Profane Sacrifice (1/Turn)"
"actions":
- "desc": "Draven makes three Gloom Dagger attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +11 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 10 (1d4 + 8) piercing damage plus 7 (3d4) necrotic\
    \ damage, and Draven can move the target up to 10 feet horizontally. If the damage\
    \ from this attack reduces a creature to 0 hit points, Draven regains a use of\
    \ Blood of the Dragon."
  "name": "Gloom Dagger"
- "desc": "Draven boils the blood of up to three creatures he can see within 60 feet\
    \ of him. Each target takes 33 (6d10) necrotic damage and must succeed on a\
    \ DC 19 Constitution saving throw or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ for 1 minute (save ends at end of turn) and knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Blood of the Dragon (1/Day)"
"bonus_actions":
- "desc": "Draven chooses a creature he can see within 30 feet of him in an area of\
    \ dim light or darkness. The creature must succeed on a DC 19 Wisdom saving throw\
    \ or move their speed in a direction chosen by Draven. A creature with advantage\
    \ on saving throws against being [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ has advantage on this saving throw, and a creature who can't be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ automatically succeeds on it."
  "name": "Creeping Dread"
"source":
- "FleeMortals"
```
^statblock