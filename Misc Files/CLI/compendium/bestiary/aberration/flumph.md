---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration
statblock: inline
aliases: ["Flumph"]
---
# [Flumph](Misc Files\CLI\compendium\bestiary\aberration/flumph.md)
*Source: Monster Manual p. 135*  

The mysterious flumphs drift through the Underdark, propelled through the air by the jets whose sound gives them their name. A flumph glows faintly, reflecting its moods in its color. Soft pink means it is amused, deep blue is sadness, green expresses curiosity, and crimson is anger.

## Intelligent and Wise

Flumphs communicate telepathically. Though they resemble jellyfish, flumphs are sentient beings of great intelligence and wisdom, possessing advanced knowledge of religion, philosophy, mathematics, and countless other subjects.

Flumphs are sensitive to the emotional states of nearby creatures. If a creature's thoughts suggest goodness, a flumph seeks that creature out. When facing creatures that exude evil, a flumph flees.

## Psionic Siphons

Flumphs feed by siphoning mental energy from psionic creatures, and they can be found lurking near communities of mind flayers, aboleths, githyanki, and githzerai. As passive parasites, they take only the mental energy they need, and most creatures feel no loss or discomfort from such feeding.

Consuming psionic energy reveals the thoughts and emotions of the creatures on which the flumphs feed. Since so many of those creatures are evil, flumphs are often subjected to thoughts, emotions, and hungers that sicken their pure nature. When flumphs encounter good-hearted adventurers, they eagerly share the dark secrets they have learned in the hopes of casting down their evil sources of energy, even if doing so means they must seek out new sources of nourishment.

## Flumph Society

Flumphs live in complex and organized groups called cloisters, within which each flumph has a place and purpose. These harmonious groupings have no need for leaders, since all flumphs contribute in their own way

```statblock
"name": "Flumph"
"size": "Small"
"type": "aberration"
"alignment": "Lawful Good"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "6"
- !!int "15"
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "11"
"speed": "5 ft., fly 30 ft."
"skillsaves":
  "Religion": !!int "4"
  "History": !!int "4"
  "Arcana": !!int "4"
"damage_vulnerabilities": "psychic"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands Undercommon but can't speak, telepathy 60 ft."
"cr": "1/8"
"traits":
- "desc": "The flumph can perceive the content of any telepathic communication used\
    \ within 60 feet of it, and it can't be [surprised](Misc%20Files/CLI/rules/conditions.md#Surprised)\
    \ by creatures with any form of telepathy."
  "name": "Advanced Telepathy"
- "desc": "If the flumph is knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
    \ roll a die. On an odd result, the flumph lands upside-down and is [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated).\
    \ At the end of each of its turns, the flumph can make a DC 10 Dexterity saving\
    \ throw, righting itself and ending the [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ condition if it succeeds."
  "name": "Prone Deficiency"
- "desc": "The flumph is immune to any effect that would sense its emotions or read\
    \ its thoughts, as well as all divination spells."
  "name": "Telepathic Shroud"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4\
    \ (1d4 + 2) piercing damage plus 2 (1d4) acid damage. At the end of each of\
    \ its turns, the target must make a DC 10 Constitution saving throw, taking 2\
    \ (1d4) acid damage on a failure or ending the recurring acid damage on a success.\
    \ A [lesser restoration](Misc%20Files/CLI/compendium/spells/lesser-restoration-xphb.md)\
    \ spell cast on the target also ends the recurring acid damage."
  "name": "Tendrils"
- "desc": "Each creature in a 15-foot cone originating from the flumph must succeed\
    \ on a DC 10 Dexterity saving throw or be coated in a foul-smelling liquid. A\
    \ coated creature exudes a horrible stench for 1d4 hours. The coated creature\
    \ is [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) as long as the\
    \ stench lasts, and other creatures are [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ while with in 5 feet of the coated creature. A creature can remove the stench\
    \ on itself by using a short rest to bathe in water, alcohol, or vinegar."
  "name": "Stench Spray (1/Day)"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/aberration/token/flumph.webp"
```
^statblock

## Environment

underdark