---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Druid"]
---
# [Druid](Misc Files\CLI\compendium\bestiary\humanoid/druid.md)
*Source: Monster Manual p. 346. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Druids dwell in forests and other secluded wilderness locations, where they protect the natural world from monsters and the encroachment of civilization. Some are tribal shamans who heal the sick, pray to animal spirits, and provide spiritual guidance.

```statblock
"name": "Druid"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "16 with [barkskin](Misc%20Files/CLI/compendium/spells/barkskin-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Nature": !!int "3"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Druidic plus any two languages"
"cr": "2"
"traits":
- "desc": "The druid is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). It has the following druid\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](Misc%20Files/CLI/compendium/spells/druidcraft-xphb.md),\
    \ [produce flame](Misc%20Files/CLI/compendium/spells/produce-flame-xphb.md), [shillelagh](Misc%20Files/CLI/compendium/spells/shillelagh-xphb.md)\n\
    \n1st level (4 slots): [entangle](Misc%20Files/CLI/compendium/spells/entangle-xphb.md),\
    \ [longstrider](Misc%20Files/CLI/compendium/spells/longstrider-xphb.md), [speak\
    \ with animals](Misc%20Files/CLI/compendium/spells/speak-with-animals-xphb.md),\
    \ [thunderwave](Misc%20Files/CLI/compendium/spells/thunderwave-xphb.md)\n\n2nd\
    \ level (3 slots): [animal messenger](Misc%20Files/CLI/compendium/spells/animal-messenger-xphb.md),\
    \ [barkskin](Misc%20Files/CLI/compendium/spells/barkskin-xphb.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning\
    \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with [shillelagh](Misc%20Files/CLI/compendium/spells/shillelagh-xphb.md)."
  "name": "Quarterstaff"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/humanoid/token/druid.webp"
```
^statblock

## Environment

coastal, mountain, grassland, hill, arctic, forest, swamp, underdark, desert