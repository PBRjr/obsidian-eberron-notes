---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
aliases: ["Mycete"]
---
# [Mycete](Misc Files\CLI\compendium\bestiary\npc/mycete-fleemortals.md)
*Source: Flee, Mortals! p. 353*  

```statblock
"name": "Mycete (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling, Controller"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "[leather armor](Misc%20Files/CLI/compendium/items/leather-armor-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"stats":
- !!int "9"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "16"
- !!int "12"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "2"
"skillsaves":
  "Nature": !!int "2"
  "Insight": !!int "5"
  "Perception": !!int "5"
  "Survival": !!int "5"
"damage_resistances": "fire"
"damage_immunities": "necrotic"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Infernal"
"cr": "1"
"traits":
- "desc": "In addition to any other spells in this stat block, Mycete can cast the\
    \ following spells, using Wisdom as the spellcasting ability (spell save DC 13):\n\
    \nAt will: [druidcraft](Misc%20Files/CLI/compendium/spells/druidcraft-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n1/day each: [fog cloud](Misc%20Files/CLI/compendium/spells/fog-cloud-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>, [pass without trace](Misc%20Files/CLI/compendium/spells/pass-without-trace-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n3/day: [locate animals or\
    \ plants](Misc%20Files/CLI/compendium/spells/locate-animals-or-plants-xphb.md)\
    \ <sup>[A](#^superscript-casting-time)</sup>\n\n| Superscript | Casting Time |\n\
    |-------------|--------------|\n| A | 1 action |\n| B | 1 bonus action |\n| R\
    \ | 1 reaction |\n| + | Longer than 1 action (see spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "Whenever Mycete is subjected to necrotic damage, she takes no damage and\
    \ instead regains a number of hit points equal to the necrotic damage dealt."
  "name": "Necrotic Absorption"
"actions":
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft.,\
    \ one target. Hit: 7 (2d6) necrotic damage, and if the target is a creature,\
    \ Mycete regains 3 (1d6) hit points."
  "name": "Parasitic Spores"
- "desc": "Mycete causes fungi to proliferate from a point she can see within 60 feet\
    \ of her. Solid surfaces in a 10-foot square centered on that point become difficult\
    \ terrain, and a creature who enters that area for the first time on a turn or\
    \ starts their turn there must succeed on a DC 13 Constitution saving throw or\
    \ be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) for 1 minute (save\
    \ ends at end of turn)."
  "name": "Fungal Growth"
- "desc": "Mycete animates three rotting zombies, who appear in unoccupied spaces\
    \ Mycete can see within 30 feet of her. The zombies act immediately after Mycete\
    \ on the same initiative count and follow her verbal orders. If Mycete dies, the\
    \ zombies are destroyed."
  "name": "Animate Husks (1/Day)"
"bonus_actions":
- "desc": "Mycete destroys a rotting zombie under her control, and the zombie violently\
    \ erupts with toxic spores.\n\nEach enemy within 5 feet of the zombie must make\
    \ a DC 13 Constitution saving throw, taking 9 (2d8) necrotic damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Spore Eruption"
"source":
- "FleeMortals"
```
^statblock