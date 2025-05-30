---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
aliases: ["Rakshasa"]
---
# [Rakshasa](Misc Files\CLI\compendium\bestiary\fiend/rakshasa.md)
*Source: Monster Manual p. 257, Eberron: Rising from the Last War. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

The rakshasa employs delicacy and misdirection in its pursuit of dominion over others. Few creatures ever see the fiend in its true form, for it can take on any guise it wants, although it prefers to masquerade as someone powerful or influential: a noble, cardinal, or rich merchant, for example. A rakshasa's true form combines the features of a human and a tiger, with one noteworthy deformity: its palms are where the backs of the hands would be on a human.

## Evil Spirits in Mortal Flesh

Rakshasas originated long ago in the Nine Hells, when powerful devils created a dark ritual to free their essence from their fiendish bodies in order to escape the Lower Planes. A rakshasa enters the Material Plane to feed its appetite for humanoid flesh and evil schemes. It selects its prey with care, taking pains to keep its presence in the world a secret.

## Evil Reborn

For a rakshasa, death on the Material Plane means an agonizing and torturous return to the Nine Hells, where its essence remains trapped until its body reforms-a process that can take months or years.

When the rakshasa is reborn, it has all the memories and knowledge of its former life, and it seeks retribution against the one who slew it. If the target has somehow slipped through its grasp, the rakshasa might punish its killer's family, friends, or descendants.

Like devils, rakshasas killed in the Nine Hells are forever destroyed.

> [!quote] A quote from Rakshasa maxim  
> 
> Slay me once, shame on you.
> 
> Slay me twice, shame on me.


```statblock
"name": "Rakshasa"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "110"
"hit_dice": "13d8 + 52"
"stats":
- !!int "14"
- !!int "17"
- !!int "18"
- !!int "13"
- !!int "16"
- !!int "20"
"speed": "40 ft."
"skillsaves":
  "Deception": !!int "10"
  "Insight": !!int "8"
"damage_vulnerabilities": "piercing from magic weapons wielded by good creatures"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Infernal"
"cr": "13"
"traits":
- "desc": "The rakshasa's innate spellcasting ability is Charisma (spell save DC 18,\
    \ +10 to hit with spell attacks). The rakshasa can innately cast the following\
    \ spells, requiring no material components:\n\nAt will: [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md),\
    \ [disguise self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md), [mage\
    \ hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md), [minor illusion](Misc%20Files/CLI/compendium/spells/minor-illusion-xphb.md)\n\
    \n1/day each: [dominate person](Misc%20Files/CLI/compendium/spells/dominate-person-xphb.md),\
    \ [fly](Misc%20Files/CLI/compendium/spells/fly-xphb.md), [plane shift](Misc%20Files/CLI/compendium/spells/plane-shift-xphb.md),\
    \ [true seeing](Misc%20Files/CLI/compendium/spells/true-seeing-xphb.md)\n\n3/day\
    \ each: [charm person](Misc%20Files/CLI/compendium/spells/charm-person-xphb.md),\
    \ [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md), [invisibility](Misc%20Files/CLI/compendium/spells/invisibility-xphb.md),\
    \ [major image](Misc%20Files/CLI/compendium/spells/major-image-xphb.md), [suggestion](Misc%20Files/CLI/compendium/spells/suggestion-xphb.md)"
  "name": "Innate Spellcasting"
- "desc": "The rakshasa can't be affected or detected by spells of 6th level or lower\
    \ unless it wishes to be. It has advantage on saving throws against all other\
    \ spells and magical effects."
  "name": "Limited Magic Immunity"
"actions":
- "desc": "The rakshasa makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage, and the target is cursed if it is a creature. The magical\
    \ curse takes effect whenever the target takes a short or long rest, filling the\
    \ target's thoughts with horrible images and dreams. The cursed target gains no\
    \ benefit from finishing a short or long rest. The curse lasts until it is lifted\
    \ by a [remove curse](Misc%20Files/CLI/compendium/spells/remove-curse-xphb.md)\
    \ spell or similar magic."
  "name": "Claw"
"source":
- "MM"
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/fiend/token/rakshasa.webp"
```
^statblock

## Environment

urban