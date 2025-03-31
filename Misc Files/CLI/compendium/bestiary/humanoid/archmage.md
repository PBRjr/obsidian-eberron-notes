---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Archmage"]
---
# [Archmage](Misc Files\CLI\compendium\bestiary\humanoid/archmage.md)
*Source: Monster Manual p. 342, Eberron: Rising from the Last War. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Archmages are powerful (and usually quite old) spellcasters dedicated to the study of the arcane arts. Benevolent ones counsel kings and queens, while evil ones rule as tyrants and pursue lichdom. Those who are neither good nor evil sequester themselves in remote towers to practice their magic without interruption.

An archmage typically has one or more apprentice mages, and an archmage's abode has numerous magical wards and guardians to discourage interlopers.

```statblock
"name": "Archmage"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Misc%20Files/CLI/compendium/spells/mage-armor-xphb.md)"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing, slashing\
  \ (from stoneskin)"
"senses": "passive Perception 12"
"languages": "any six languages"
"cr": "12"
"traits":
- "desc": "The archmage is an 18th-level spellcaster. Its spellcasting ability is\
    \ Intelligence (spell save DC 17, +9 to hit with spell attacks). The archmage\
    \ can cast [disguise self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md)\
    \ and [invisibility](Misc%20Files/CLI/compendium/spells/invisibility-xphb.md)\
    \ at will and has the following wizard spells prepared:\n\nAt will: [disguise\
    \ self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md), [invisibility](Misc%20Files/CLI/compendium/spells/invisibility-xphb.md)\n\
    \nCantrips (at will): [fire bolt](Misc%20Files/CLI/compendium/spells/fire-bolt-xphb.md),\
    \ [light](Misc%20Files/CLI/compendium/spells/light-xphb.md), [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md),\
    \ [prestidigitation](Misc%20Files/CLI/compendium/spells/prestidigitation-xphb.md),\
    \ [shocking grasp](Misc%20Files/CLI/compendium/spells/shocking-grasp-xphb.md)\n\
    \n1st level (4 slots): [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md),\
    \ [identify](Misc%20Files/CLI/compendium/spells/identify-xphb.md), [mage armor](Misc%20Files/CLI/compendium/spells/mage-armor-xphb.md),\
    \ [magic missile](Misc%20Files/CLI/compendium/spells/magic-missile-xphb.md)\n\n\
    2nd level (3 slots): [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md),\
    \ [mirror image](Misc%20Files/CLI/compendium/spells/mirror-image-xphb.md), [misty\
    \ step](Misc%20Files/CLI/compendium/spells/misty-step-xphb.md)\n\n3rd level\
    \ (3 slots): [counterspell](Misc%20Files/CLI/compendium/spells/counterspell-xphb.md),\
    \ [fly](Misc%20Files/CLI/compendium/spells/fly-xphb.md), [lightning bolt](Misc%20Files/CLI/compendium/spells/lightning-bolt-xphb.md)\n\
    \n4th level (3 slots): [banishment](Misc%20Files/CLI/compendium/spells/banishment-xphb.md),\
    \ [fire shield](Misc%20Files/CLI/compendium/spells/fire-shield-xphb.md), [stoneskin](Misc%20Files/CLI/compendium/spells/stoneskin-xphb.md)\n\
    \n5th level (3 slots): [cone of cold](Misc%20Files/CLI/compendium/spells/cone-of-cold-xphb.md),\
    \ [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md), [wall of force](Misc%20Files/CLI/compendium/spells/wall-of-force-xphb.md)\n\
    \n6th level (1 slots): [globe of invulnerability](Misc%20Files/CLI/compendium/spells/globe-of-invulnerability-xphb.md)\n\
    \n7th level (1 slots): [teleport](Misc%20Files/CLI/compendium/spells/teleport-xphb.md)\n\
    \n8th level (1 slots): [mind blank](Misc%20Files/CLI/compendium/spells/mind-blank-xphb.md)\n\
    \n9th level (1 slots): [time stop](Misc%20Files/CLI/compendium/spells/time-stop-xphb.md)\n\
    \nThe archmage casts these spells on itself before combat."
  "name": "Spellcasting"
- "desc": "The archmage has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "MM"
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/humanoid/token/archmage.webp"
```
^statblock

## Environment

urban