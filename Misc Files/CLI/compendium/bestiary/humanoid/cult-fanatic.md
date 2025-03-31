---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Cult Fanatic"]
---
# [Cult Fanatic](Misc Files\CLI\compendium\bestiary\humanoid/cult-fanatic.md)
*Source: Monster Manual p. 345. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Fanatics are often part of a cult's leadership, using their charisma and dogma to influence and prey on those of weak will. Most are interested in personal power above all else

```statblock
"name": "Cult Fanatic"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "13"
"ac_class": "[leather armor](Misc%20Files/CLI/compendium/items/leather-armor-xphb.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "11"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Religion": !!int "2"
  "Persuasion": !!int "4"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "2"
"traits":
- "desc": "The fanatic is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 11, +3 to hit with spell attacks). The fanatic has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](Misc%20Files/CLI/compendium/spells/light-xphb.md),\
    \ [sacred flame](Misc%20Files/CLI/compendium/spells/sacred-flame-xphb.md), [thaumaturgy](Misc%20Files/CLI/compendium/spells/thaumaturgy-xphb.md)\n\
    \n1st level (4 slots): [command](Misc%20Files/CLI/compendium/spells/command-xphb.md),\
    \ [inflict wounds](Misc%20Files/CLI/compendium/spells/inflict-wounds-xphb.md),\
    \ [shield of faith](Misc%20Files/CLI/compendium/spells/shield-of-faith-xphb.md)\n\
    \n2nd level (3 slots): [hold person](Misc%20Files/CLI/compendium/spells/hold-person-xphb.md),\
    \ [spiritual weapon](Misc%20Files/CLI/compendium/spells/spiritual-weapon-xphb.md)"
  "name": "Spellcasting"
- "desc": "The fanatic has advantage on saving throws against being [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ or [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)."
  "name": "Dark Devotion"
"actions":
- "desc": "The fanatic makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one creature. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/humanoid/token/cult-fanatic.webp"
```
^statblock

## Environment

urban