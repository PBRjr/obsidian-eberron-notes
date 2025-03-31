---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
aliases: ["Magewright"]
---
# [Magewright](Misc Files\CLI\compendium\bestiary\humanoid/magewright-erlw.md)
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](Misc%20Files/CLI/compendium/spells/prestidigitation-xphb.md) to heat and season food, while a blacksmith uses [mending](Misc%20Files/CLI/compendium/spells/mending-xphb.md) to perform minor repairs and [guidance](Misc%20Files/CLI/compendium/spells/guidance-xphb.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

`dice: [](magewright-erlw.md#^magewright-specialties)`

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | [Guidance](Misc%20Files/CLI/compendium/spells/guidance-xphb.md), [mending](Misc%20Files/CLI/compendium/spells/mending-xphb.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](Misc%20Files/CLI/compendium/spells/minor-illusion-xphb.md), [thaumaturgy](Misc%20Files/CLI/compendium/spells/thaumaturgy-xphb.md). Ritual only: [disguise self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md). | [Performance](Misc%20Files/CLI/rules/skills.md#Performance) (+3) |
| 3 | Healer | [Resistance](Misc%20Files/CLI/compendium/spells/resistance-xphb.md), [spare the dying](Misc%20Files/CLI/compendium/spells/spare-the-dying-xphb.md). Ritual only: [detect poison and disease](Misc%20Files/CLI/compendium/spells/detect-poison-and-disease-xphb.md), [lesser restoration](Misc%20Files/CLI/compendium/spells/lesser-restoration-xphb.md) (1 hour). | [Medicine](Misc%20Files/CLI/rules/skills.md#Medicine) (+4), [herbalism kit](Misc%20Files/CLI/compendium/items/herbalism-kit-xphb.md) |
| 4 | Lamplighter | [Light](Misc%20Files/CLI/compendium/spells/light-xphb.md). Ritual only: [continual flame](Misc%20Files/CLI/compendium/spells/continual-flame-xphb.md) (1 hour). | [Tinker's tools](Misc%20Files/CLI/compendium/items/tinkers-tools-xphb.md) |
| 5 | Locksmith | [Mending](Misc%20Files/CLI/compendium/spells/mending-xphb.md). Ritual only: [arcane lock](Misc%20Files/CLI/compendium/spells/arcane-lock-xphb.md) (1 hour), [knock](Misc%20Files/CLI/compendium/spells/knock-xphb.md). | [Thieves' tools](Misc%20Files/CLI/compendium/items/thieves-tools-xphb.md), [tinker's tools](Misc%20Files/CLI/compendium/items/tinkers-tools-xphb.md) |
| 6 | Mediator | [Guidance](Misc%20Files/CLI/compendium/spells/guidance-xphb.md). Ritual only: [comprehend languages](Misc%20Files/CLI/compendium/spells/comprehend-languages-xphb.md), [zone of truth](Misc%20Files/CLI/compendium/spells/zone-of-truth-xphb.md). | [Insight](Misc%20Files/CLI/rules/skills.md#Insight) (+4), [Persuasion](Misc%20Files/CLI/rules/skills.md#Persuasion) (+3) |
| 7 | Medium | [Minor illusion](Misc%20Files/CLI/compendium/spells/minor-illusion-xphb.md). Ritual only: [speak with dead](Misc%20Files/CLI/compendium/spells/speak-with-dead-xphb.md). | [Deception](Misc%20Files/CLI/rules/skills.md#Deception) (+3), [Religion](Misc%20Files/CLI/rules/skills.md#Religion) (+4) |
| 8 | Oracle | [Guidance](Misc%20Files/CLI/compendium/spells/guidance-xphb.md). Ritual only: [augury](Misc%20Files/CLI/compendium/spells/augury-xphb.md), [divination](Misc%20Files/CLI/compendium/spells/divination-xphb.md) (1 hour). | [History](Misc%20Files/CLI/rules/skills.md#History) (+4), [Religion](Misc%20Files/CLI/rules/skills.md#Religion) (+4) |
^magewright-specialties

```statblock
"name": "Magewright (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "13"
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "4"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "0"
"traits":
- "desc": "The magewright's spellcasting ability is Intelligence (spell save DC 12).\
    \ To cast one of its rituals, the magewright must provide additional material\
    \ components whose value in gold pieces is 20 times the spell's level. These components\
    \ are consumed when the ritual is finished. The magewright knows the following\
    \ spells:\n\nAt will: [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md),\
    \ [prestidigitation](Misc%20Files/CLI/compendium/spells/prestidigitation-xphb.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/humanoid/token/magewright-erlw.webp"
```
^statblock