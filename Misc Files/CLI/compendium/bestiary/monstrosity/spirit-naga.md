---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Spirit Naga"]
---
# [Spirit Naga](Misc Files\CLI\compendium\bestiary\monstrosity/spirit-naga.md)
*Source: Monster Manual p. 234. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Spirit nagas live in gloom and spitefulness, constantly plotting vengeance against creatures that have wronged them-or that they believe have wronged them. Lairing in dismal caverns and ruins, they devote their time to developing new spells and enslaving the mortals with which they surround themselves. A spirit naga likes to charm its foes, drawing them close so that it can sink its poisonous fangs into their flesh.

> [!quote] A quote from Explictica Defilus, spirit naga  
> 
> If you destroy me, I will return, and everyone you care about will suffer for it.

## Nagas

Nagas are intelligent serpents that inhabit the ruins of the past, amassing arcane treasures and knowledge.

The first nagas were created as immortal guardians by a humanoid race long lost to history. When this race died out, the nagas deemed themselves the rightful inheritors of their masters' treasures and magical lore. Industrious and driven, nagas occasionally venture out from their lairs to track down magic items or rare spellbooks.

Nagas never feel the ravages of time or succumb to sickness. Even if it is struck down, a naga's immortal spirit reforms in a new body in a matter of days, ready to continue its eternal work.

### Benevolent Dictators and Brutal Tyrants

A naga rules its domain with absolute authority. Whether it rules with compassion or by terrorizing its subjects, the naga believes itself the master of all other creatures that inhabit its domain.

### Rivalry

Nagas have a long-standing enmity with the yuan-ti, with each race seeing itself as the epitome of serpentine evolution. Though cooperation between them is rare, nagas and yuan-ti sometimes set aside their differences to work toward common objectives. However, yuan-ti always chafe under a naga's authority.

### Immortal Nature

A naga doesn't require air, food, drink, or sleep.

```statblock
"name": "Spirit Naga"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"stats":
- !!int "18"
- !!int "17"
- !!int "14"
- !!int "16"
- !!int "15"
- !!int "16"
"speed": "40 ft."
"saves":
  "Charisma": !!int "6"
  "Dexterity": !!int "6"
  "Wisdom": !!int "5"
  "Constitution": !!int "5"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Common"
"cr": "8"
"traits":
- "desc": "The naga is a 10th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 14, +6 to hit with spell attacks), and it needs only verbal\
    \ components to cast its spells. It has the following wizard spells prepared:\n\
    \nCantrips (at will): [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md),\
    \ [minor illusion](Misc%20Files/CLI/compendium/spells/minor-illusion-xphb.md),\
    \ [ray of frost](Misc%20Files/CLI/compendium/spells/ray-of-frost-xphb.md)\n\n\
    1st level (4 slots): [charm person](Misc%20Files/CLI/compendium/spells/charm-person-xphb.md),\
    \ [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md), [sleep](Misc%20Files/CLI/compendium/spells/sleep-xphb.md)\n\
    \n2nd level (3 slots): [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md),\
    \ [hold person](Misc%20Files/CLI/compendium/spells/hold-person-xphb.md)\n\n3rd\
    \ level (3 slots): [lightning bolt](Misc%20Files/CLI/compendium/spells/lightning-bolt-xphb.md),\
    \ [water breathing](Misc%20Files/CLI/compendium/spells/water-breathing-xphb.md)\n\
    \n4th level (3 slots): [blight](Misc%20Files/CLI/compendium/spells/blight-xphb.md),\
    \ [dimension door](Misc%20Files/CLI/compendium/spells/dimension-door-xphb.md)\n\
    \n5th level (2 slots): [dominate person](Misc%20Files/CLI/compendium/spells/dominate-person-xphb.md)"
  "name": "Spellcasting"
- "desc": "If it dies, the naga returns to life in 1d6 days and regains all its\
    \ hit points. Only a [wish](Misc%20Files/CLI/compendium/spells/wish-xphb.md) spell\
    \ can prevent this trait from functioning."
  "name": "Rejuvenation"
"actions":
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one creature. Hit:\
    \ 7 (1d6 + 4) piercing damage, and the target must make a DC 13 Constitution\
    \ saving throw, taking 31 (7d8) poison damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Bite"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/monstrosity/token/spirit-naga.webp"
```
^statblock

## Environment

underdark