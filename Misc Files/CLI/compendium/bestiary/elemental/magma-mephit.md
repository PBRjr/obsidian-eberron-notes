---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/elemental
statblock: inline
aliases: ["Magma Mephit"]
---
# [Magma Mephit](Misc Files\CLI\compendium\bestiary\elemental/magma-mephit.md)
*Source: Monster Manual p. 216. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

## Mephits

Mephits are capricious, imp-like creatures native to the elemental planes. They come in six varieties, each one representing the mixture of two elements.

Ageless tricksters, mephits gather in large numbers on the Elemental Planes and in the Elemental Chaos. They also find their way to the Material Plane, where they prefer to dwell in places where their base elements are abundant. For example, a magma mephit is composed of earth and fire, and it favors volcanic lairs, while an ice mephit, which is composed of air and water, favors frigid locales.

### Elemental Nature

A mephit doesn't require food, drink, or sleep.

## Magma Mephit

Composed of earth and fire, magma mephits glow a dull red color as they perspire beads of molten lava. They are slow to comprehend the meaning of others' words and actions.

```statblock
"name": "Magma Mephit"
"size": "Small"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"stats":
- !!int "8"
- !!int "12"
- !!int "12"
- !!int "7"
- !!int "10"
- !!int "10"
"speed": "30 ft., fly 30 ft."
"skillsaves":
  "Stealth": !!int "3"
"damage_vulnerabilities": "cold"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Ignan, Terran"
"cr": "1/2"
"traits":
- "desc": "The mephit can innately cast [heat metal](Misc%20Files/CLI/compendium/spells/heat-metal-xphb.md)\
    \ (spell save DC 10), requiring no material components. Its innate spellcasting\
    \ ability is Charisma.\n\nAt will: [heat metal](Misc%20Files/CLI/compendium/spells/heat-metal-xphb.md)"
  "name": "Innate Spellcasting (1/Day)"
- "desc": "When the mephit dies, it explodes in a burst of lava. Each creature within\
    \ 5 feet of it must make a DC 11 Dexterity saving throw, taking 7 (2d6) fire\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Death Burst"
- "desc": "While the mephit remains motionless, it is indistinguishable from an ordinary\
    \ mound of magma."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. Hit: 3\
    \ (1d4 + 1) slashing damage plus 2 (1d4) fire damage."
  "name": "Claws"
- "desc": "The mephit exhales a 15-foot cone of fire. Each creature in that area must\
    \ make a DC 11 Dexterity saving throw, taking 7 (2d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 6)"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/elemental/token/magma-mephit.webp"
```
^statblock

## Environment

underdark