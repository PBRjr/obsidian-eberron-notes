---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/support
statblock: inline
aliases: ["Green Hag"]
---
# [Green Hag](Misc Files\CLI\compendium\bestiary\fey/green-hag-fleemortals.md)
*Source: Flee, Mortals! p. 137*  

```statblock
"name": "Green Hag (FleeMortals)"
"size": "Medium"
"type": "fey"
"subtype": "Support"
"alignment": "typically  Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "12"
- !!int "16"
- !!int "16"
- !!int "14"
- !!int "15"
- !!int "18"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Deception": !!int "6"
  "Stealth": !!int "5"
  "Perception": !!int "4"
  "Arcana": !!int "4"
"damage_resistances": "poison"
"condition_immunities": "[poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Primordial, Sylvan"
"cr": "3"
"traits":
- "desc": "In addition to any other spells in this stat block, the hag can cast the\
    \ following spells, using Charisma as the spellcasting ability (spell save DC\
    \ 14):\n\nAt will: [alter self](Misc%20Files/CLI/compendium/spells/alter-self-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [dancing lights](Misc%20Files/CLI/compendium/spells/dancing-lights-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [minor illusion](Misc%20Files/CLI/compendium/spells/minor-illusion-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n1/day: [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md)\
    \ <sup>[+](#^superscript-casting-time)</sup>\n\n3/day each: [animal messenger](Misc%20Files/CLI/compendium/spells/animal-messenger-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [legend lore](Misc%20Files/CLI/compendium/spells/legend-lore-xphb.md)\
    \ <sup>[+](#^superscript-casting-time)</sup>, [speak with animals](Misc%20Files/CLI/compendium/spells/speak-with-animals-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time |\n\
    |-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action |\n| R\
    \ | 1 reaction |\n| + | Longer than 1 action (see spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "Each ally within 30 feet of the hag deals an extra 3 (1d6) poison damage\
    \ with weapon attacks, provided the hag isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)."
  "name": "Envenom"
"actions":
- "desc": "The hag makes one Poison Claw attack and uses Granny Says."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) slashing damage plus 3 (1d6) poison damage."
  "name": "Poison Claw"
- "desc": "The hag affects one other willing creature they can see within 30 feet\
    \ of them with one of the following effects:\n\n- The target magically switches\
    \ places with the hag.  \n- The target uses their reaction, if available, to make\
    \ an attack.  "
  "name": "Granny Says"
- "desc": "The hag chooses a creature they can see within 60 feet of them and attempts\
    \ to transform them into a Beast of the hag's choice with a challenge rating of\
    \ 2 or lower. The target must succeed on a DC 14 Wisdom saving throw or be transformed\
    \ for 1 minute (save ends at end of turn). While transformed, the target's game\
    \ statistics are replaced by the statistics of the chosen Beast, though they retain\
    \ their alignment, personality, and Intelligence, Wisdom, and Charisma scores.\
    \ The target's gear melds into the new form. They can't activate, use, wield,\
    \ or otherwise benefit from any of their equipment. They can't speak or cast spells\
    \ but can take any action the Beast can take. If the target drops to 0 hit points\
    \ while in this form, they revert back to their original form with half the number\
    \ of hit points they had before they transformed."
  "name": "Naughty Mousey (3/Day; 5th-Level Spell; Concentration)"
"reactions":
- "desc": "When an ally within 30 feet of the hag is targeted with an attack, the\
    \ hag can turn the target [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ until the start of the target's next turn, potentially imposing disadvantage\
    \ on the triggering attack roll and causing it to miss. To use this reaction,\
    \ the hag must be able to see the ally and the attacker."
  "name": "Get Gone"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Green%20Hag.png"
```
^statblock