---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
aliases: ["Argan Rael"]
---
# [Argan Rael](Misc Files\CLI\compendium\bestiary\npc/argan-rael-fleemortals.md)
*Source: Flee, Mortals! p. 382*  

```statblock
"name": "Argan Rael (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling, Artillery"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "18 with [mage armor](Misc%20Files/CLI/compendium/spells/mage-armor-xphb.md)"
"hp": !!int "104"
"hit_dice": "19d8 + 19"
"stats":
- !!int "9"
- !!int "20"
- !!int "12"
- !!int "24"
- !!int "10"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "10"
  "Constitution": !!int "4"
"skillsaves":
  "Investigation": !!int "10"
  "Perception": !!int "3"
  "History": !!int "10"
  "Arcana": !!int "10"
"damage_resistances": "fire, necrotic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Infernal"
"cr": "7"
"traits":
- "desc": "In addition to any other spells in this stat block, Argan can cast the\
    \ following spells, using Intelligence as his spellcasting ability (spell save\
    \ DC 18):\n\nAt will: [dancing lights](Misc%20Files/CLI/compendium/spells/dancing-lights-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [message](Misc%20Files/CLI/compendium/spells/message-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [prestidigitation](Misc%20Files/CLI/compendium/spells/prestidigitation-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, \n\n2/day each: [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [mage armor](Misc%20Files/CLI/compendium/spells/mage-armor-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [sending](Misc%20Files/CLI/compendium/spells/sending-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time |\n\
    |-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action |\n| R\
    \ | 1 reaction |\n| + | Longer than 1 action (see spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "Argan has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "Damage from Argan's spell attacks ignore the target's damage resistances."
  "name": "Pervasive Magic"
"actions":
- "desc": "Argan makes three Arcane Lance attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +10 to hit, reach 5 ft. or range 90 ft.,\
    \ one target. Hit: 17 (5d6) force damage, and Argan moves the target up to\
    \ 15 feet horizontally."
  "name": "Arcane Lance (Cantrip)"
- "desc": "Argan calls down lightning on up to three creatures he can see within 30\
    \ feet of him. Each target must make a DC 18 Constitution saving throw. On a failed\
    \ save, a target takes 21 (6d6) lightning damage and their speed is halved until\
    \ the end of their next turn. On a successful save, a target takes half as much\
    \ damage and their speed is not halved."
  "name": "Lightning Volley (3rd-Level Spell)"
- "desc": "Argan sculpts a fiery explosion centered on a point within 90 feet of him.\
    \ Each creature of his choice in a 20-foot-radius sphere centered on that point\
    \ must make a DC 18 Dexterity saving throw, taking 42 (12d6) fire damage on\
    \ a failed save, or half as much damage on a successful one."
  "name": "Fireball (1/Day; 7th-Level Spell)"
"bonus_actions":
- "desc": "Argan teleports up to 30 feet to an unoccupied space he can see."
  "name": "Misty Step (2/Day; 2nd-Level Spell)"
"source":
- "FleeMortals"
```
^statblock