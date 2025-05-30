---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Lamia"]
---
# [Lamia](Misc Files\CLI\compendium\bestiary\monstrosity/lamia.md)
*Source: Monster Manual p. 201. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Ruined desert cities and the tombs of forgotten monarchs make perfect lairs for the wicked lamias. These decadent monsters take what has been forgotten and make it the seat of their hedonistic rule, surrounding themselves with sycophants. Lamias rely on [jackalweres](Misc%20Files/CLI/compendium/bestiary/humanoid/jackalwere.md) to perform various tasks, sending them across the wastes to capture slaves or steal treasures from caravans, encampments, or villages, concealed by the lamia's magic as they attack.

A lamia has a beautiful humanoid upper body that merges into a powerful four-legged leonine form. Its vicious black claws speak to its predatory nature, as does its hunger for torture and humanoid flesh.

## Tyrants of Pleasure

Lamias adorn their crumbling havens with finery stolen from passing caravans, then use magic to further accentuate their lairs, masking decay with illusion. A lair's breathtaking gardens, finely decorated apartments, and numerous slaves seem at odds with its remoteness and state of ruin.

Using its intoxicating touch, a lamia weakens the minds of its enemies, making them more susceptible to its enchantment spells and turning them into its slaves. Those it beguiles with [geas](Misc%20Files/CLI/compendium/spells/geas-xphb.md) spells are pitted against each other in elaborate contests for the lamia's amusement.

## Vain Predators

Always anxious to gain more wealth and slaves, a lamia uses a pool of water or a mirror in conjunction with a [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md) spell to view its domain. A lamia uses this power to watch over trade routes and nearby settlements, or to seek out objects and creatures it fancies.

Lamias are particularly fond of seeking out adventurers with pure hearts to seduce and corrupt to evil, savoring the destruction of their virtue. They use their magic to lure potential victims to their lairs, relying on illusion and their thralls to capture hapless foes. Lamias prize beauty and strength above all else, however. Any prisoner that falls short of their esteem becomes the main course in a horrible feast, or is set free to die while wandering the wastes.

As long as they have slaves to face their enemies, lamias fight from the fringes, beguiling foes with magic if they can. A lamia pressed into melee never stays there for long, shredding flesh with claw and dagger before springing away to safety.

## Minions of Graz'zt

The demon lord Graz'zt creates lamias from his mortal servants, granting them immortality in return for monstrous power and an oath of fealty. Graz'zt sometimes tasks lamias with guarding locations important to him, but lamias in his service remain free to spread their evil as they see fit.

```statblock
"name": "Lamia"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d10 + 26"
"stats":
- !!int "16"
- !!int "13"
- !!int "15"
- !!int "14"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "7"
  "Stealth": !!int "3"
  "Insight": !!int "4"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Common"
"cr": "4"
"traits":
- "desc": "The lamia's innate spellcasting ability is Charisma (spell save DC 13).\
    \ It can innately cast the following spells, requiring no material components.\n\
    \nAt will: [disguise self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md)\
    \ (any humanoid form), [major image](Misc%20Files/CLI/compendium/spells/major-image-xphb.md)\n\
    \n1/day: [geas](Misc%20Files/CLI/compendium/spells/geas-xphb.md)\n\n3/day\
    \ each: [charm person](Misc%20Files/CLI/compendium/spells/charm-person-xphb.md),\
    \ [mirror image](Misc%20Files/CLI/compendium/spells/mirror-image-xphb.md), [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md),\
    \ [suggestion](Misc%20Files/CLI/compendium/spells/suggestion-xphb.md)"
  "name": "Innate Spellcasting"
"actions":
- "desc": "The lamia makes two attacks: one with its claws and one with its dagger\
    \ or Intoxicating Touch."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d10 + 3) slashing damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Dagger"
- "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one creature. Hit: The\
    \ target is magically cursed for 1 hour. Until the curse ends, the target has\
    \ disadvantage on Wisdom saving throws and all ability checks."
  "name": "Intoxicating Touch"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/monstrosity/token/lamia.webp"
```
^statblock

## Environment

desert