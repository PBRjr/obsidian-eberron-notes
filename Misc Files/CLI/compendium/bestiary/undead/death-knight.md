---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Death Knight"]
---
# [Death Knight](Misc Files\CLI\compendium\bestiary\undead/death-knight.md)
*Source: Monster Manual p. 47*  

When a paladin that falls from grace dies without seeking atonement, dark powers can transform the once-mortal knight into a hateful undead creature. A death knight is a skeletal warrior clad in fearsome plate armor. Beneath its helmet, one can see the knight's skull with malevolent pinpoints of light burning in its eye sockets.

## Eldritch Power

The death knight retains the ability to cast divine spells. However, no death knight can use its magic to heal. A death knight also attracts and commands lesser undead, although death knights that serve powerful fiends might have fiendish followers instead. Death knights often use warhorse skeletons and nightmares as mounts.

## Immortal Until Redeemed

A death knight can arise anew even after it has been destroyed. Only when it atones for a life of wickedness or finds redemption can it finally escape its undead purgatory and truly perish.

## Undead Nature

A death knight doesn't require air, food, drink, or sleep.

> [!note] Lord Soth
> 
> Lord Soth began his fall from grace with an act of heroism, saving an elf named Isolde from an ogre. Soth and Isolde fell in love, but Soth was already married. He had a servant dispose of his wife and was charged with murder, but fled with Isolde. When his castle fell under siege, he prayed for guidance and was told that he must atone for his misdeeds by completing a quest, but growing fears about Isolde's fidelity caused him to abandon his quest. Because his mission was not accomplished, a great cataclysm swept the land. When Isolde gave birth to a son, Soth refused to believe that the child was his and slew them both. All were incinerated in a fire that swept through the castle, yet Soth would find no rest in death, becoming a death knight.
^lord-soth

```statblock
"name": "Death Knight"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"ac_class": "[plate armor](Misc%20Files/CLI/compendium/items/plate-armor-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "180"
"hit_dice": "19d8 + 95"
"stats":
- !!int "20"
- !!int "11"
- !!int "20"
- !!int "12"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "6"
  "Wisdom": !!int "9"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Abyssal, Common"
"cr": "17"
"traits":
- "desc": "The death knight is a 19th-level spellcaster. Its spellcasting ability\
    \ is Charisma (spell save DC 18, +10 to hit with spell attacks). It has the\
    \ following paladin spells prepared:\n\n1st level (4 slots): [command](Misc%20Files/CLI/compendium/spells/command-xphb.md),\
    \ [compelled duel](Misc%20Files/CLI/compendium/spells/compelled-duel-xphb.md),\
    \ [searing smite](Misc%20Files/CLI/compendium/spells/searing-smite-xphb.md)\n\n\
    2nd level (3 slots): [hold person](Misc%20Files/CLI/compendium/spells/hold-person-xphb.md),\
    \ [magic weapon](Misc%20Files/CLI/compendium/spells/magic-weapon-xphb.md)\n\n\
    3rd level (3 slots): [dispel magic](Misc%20Files/CLI/compendium/spells/dispel-magic-xphb.md),\
    \ [elemental weapon](Misc%20Files/CLI/compendium/spells/elemental-weapon-xphb.md)\n\
    \n4th level (3 slots): [banishment](Misc%20Files/CLI/compendium/spells/banishment-xphb.md),\
    \ [staggering smite](Misc%20Files/CLI/compendium/spells/staggering-smite-xphb.md)\n\
    \n5th level (2 slots): [destructive wave](Misc%20Files/CLI/compendium/spells/destructive-wave-xphb.md)\
    \ (necrotic)"
  "name": "Spellcasting"
- "desc": "The death knight has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "Unless the death knight is [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ it and undead creatures of its choice within 60 feet of it have advantage on\
    \ saving throws against features that turn undead."
  "name": "Marshal Undead"
"actions":
- "desc": "The death knight makes three longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 9\
    \ (1d8 + 5) slashing damage, or 10 (1d10 + 5) slashing damage if used with\
    \ two hands, plus 18 (4d8) necrotic damage."
  "name": "Longsword"
- "desc": "The death knight hurls a magical ball of fire that explodes at a point\
    \ it can see within 120 feet of it. Each creature in a 20-foot-radius sphere centered\
    \ on that point must make a DC 18 Dexterity saving throw. The sphere spreads around\
    \ corners. A creature takes 35 (10d6) fire damage and 35 (10d6) necrotic damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Hellfire Orb (1/Day)"
"reactions":
- "desc": "The death knight adds 6 to its AC against one melee attack that would hit\
    \ it. To do so, the death knight must see the attacker and be wielding a melee\
    \ weapon."
  "name": "Parry"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/undead/token/death-knight.webp"
```
^statblock