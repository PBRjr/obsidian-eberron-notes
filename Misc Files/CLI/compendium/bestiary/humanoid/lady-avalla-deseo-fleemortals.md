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
aliases: ["Lady Avalla Deseo"]
---
# [Lady Avalla Deseo](Misc Files\CLI\compendium\bestiary\humanoid/lady-avalla-deseo-fleemortals.md)
*Source: Flee, Mortals! p. 365*  

```statblock
"name": "Lady Avalla Deseo (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Controller"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Misc%20Files/CLI/compendium/spells/mage-armor-xphb.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "20"
- !!int "10"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
  "Intelligence": !!int "7"
  "Constitution": !!int "4"
"skillsaves":
  "Investigation": !!int "7"
  "History": !!int "7"
  "Arcana": !!int "7"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "In addition to any other spells in this stat block, Avalla can cast the\
    \ following spells, using Intelligence as the spellcasting ability (spell save\
    \ DC 15):\n\nAt will: [light](Misc%20Files/CLI/compendium/spells/light-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [message](Misc%20Files/CLI/compendium/spells/message-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, \n\n1/day each: [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [disguise self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [sending](Misc%20Files/CLI/compendium/spells/sending-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n3/day each: [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [mage armor](Misc%20Files/CLI/compendium/spells/mage-armor-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time |\n\
    |-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action |\n| R\
    \ | 1 reaction |\n| + | Longer than 1 action (see spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "When Avalla makes an attack, she has advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
- "desc": "Avalla has advantage on saving throws against powers, spells, and other\
    \ supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
    \ one creature. Hit: 15 (3d6 + 5) lightning damage, and Avalla can move the\
    \ target up to 15 feet horizontally."
  "name": "Lightning Lash (Cantrip)"
- "desc": "Avalla projects a terrifying illusion of the High Command to each enemy\
    \ in a 30-foot cone. Each target must succeed on a DC 15 Wisdom saving throw or\
    \ take 21 (6d6) psychic damage and be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of each member of the High Command for 1 minute (save ends at end of turn)."
  "name": "Iron Terror (1/Day; 4th-Level Spell)"
- "desc": "Avalla conjures animated iron chains at a point she can see on the ground\
    \ within 60 feet of her. The chains fill a 15-foot- square on the ground centered\
    \ on that point and last for 1 minute. When a creature enters that area for the\
    \ first time on a turn or starts their turn there, they must succeed on a DC 15\
    \ Dexterity saving throw or be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ (save ends at start of turn). A creature [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ in this way takes 7 (2d6) bludgeoning damage at the end of each of their turns."
  "name": "Iron Shackles (1/Day; 3rd-Level Spell; Concentration)"
- "desc": "If not in the Cyst, Avalla teleports to the Cyst. If in the Cyst, she teleports\
    \ to a place she has visited."
  "name": "Iron Ring (2/Day)"
"reactions":
- "desc": "When Avalla isn't in the Cyst and an ally she can see within 60 feet of\
    \ her drops to 0 hit points, she expends a use of Iron Ring and teleports herself\
    \ to the Cyst along with each willing ally within 60 feet of her who isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)."
  "name": "Escape Ring"
- "desc": "When a creature Avalla can see within 60 feet of her casts a spell, she\
    \ taps into the caster's mind and sabotages their magic. The creature can choose\
    \ either to cast the spell then take 3 (1d6) psychic damage per level of the\
    \ spell cast, or to let the spell fail. If the spell fails, the creature's spell\
    \ slot is expended with no effect and their action is wasted."
  "name": "Spellcasting Feedback"
"source":
- "FleeMortals"
```
^statblock