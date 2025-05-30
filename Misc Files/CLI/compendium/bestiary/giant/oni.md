---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
aliases: ["Oni"]
---
# [Oni](Misc Files\CLI\compendium\bestiary\giant/oni.md)
*Source: Monster Manual p. 239, Eberron: Rising from the Last War. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

In nursery rhymes, oni are fearsome bogeymen that haunt the nightmares of children and adults alike, yet they are very real and always hungry. They find human babies especially delicious. Oni look like demonic ogres with blue or green skin, dark hair, and a pair of short ivory horns protruding from their foreheads. Their eyes are dark with strikingly white pupils, and their teeth and claws are jet black.

## Night Haunters

By the light of day, an oni hides its true form with magic, gaining the trust of those it intends to betray when darkness descends. These creatures can change their size as well as their shape, appearing as humanoids as they pass through towns, pretending to be travelers, woodcutters, or frontier folk. In such a form, an oni takes stock of the selection of humanoids in a settlement and devises ways to abduct and devour some of them.

## Magical Ogres

Oni are sometimes called ogre mages because of their innate magical ability. Though they are only distantly related to true ogres, they share the ogres' habit of joining forces with other evil creatures. An oni serves a master if doing so proves lucrative or provides it with a luxurious, well-defended home. Oni covet magic, and they work for evil wizards and hags in exchange for useful magic items.

> [!quote] A quote from Children's rhyme  
> 
> Lock the door, blow out the light;
> 
> The hungry oni haunts the night.
> 
> Hide and tremble, little one;
> 
> The oni wants to have some fun.
> 
> Hear it scratching on the door;
> 
> See its shadow cross the floor.
> 
> The sun won't rise for quite a while;
> 
> Till then, beware the oni's smile.


```statblock
"name": "Oni"
"size": "Large"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[chain mail](Misc%20Files/CLI/compendium/items/chain-mail-xphb.md)"
"hp": !!int "110"
"hit_dice": "13d10 + 39"
"stats":
- !!int "19"
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "12"
- !!int "15"
"speed": "30 ft., fly 30 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "3"
  "Wisdom": !!int "4"
  "Constitution": !!int "6"
"skillsaves":
  "Deception": !!int "8"
  "Perception": !!int "4"
  "Arcana": !!int "5"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Giant"
"cr": "7"
"traits":
- "desc": "The oni's innate spellcasting ability is Charisma (spell save DC 13). The\
    \ oni can innately cast the following spells, requiring no material components:\n\
    \nAt will: [darkness](Misc%20Files/CLI/compendium/spells/darkness-xphb.md),\
    \ [invisibility](Misc%20Files/CLI/compendium/spells/invisibility-xphb.md)\n\n\
    1/day each: [charm person](Misc%20Files/CLI/compendium/spells/charm-person-xphb.md),\
    \ [cone of cold](Misc%20Files/CLI/compendium/spells/cone-of-cold-xphb.md), [gaseous\
    \ form](Misc%20Files/CLI/compendium/spells/gaseous-form-xphb.md), [sleep](Misc%20Files/CLI/compendium/spells/sleep-xphb.md)"
  "name": "Innate Spellcasting"
- "desc": "The oni's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "The oni regains 10 hit points at the start of its turn if it has at least\
    \ 1 hit point."
  "name": "Regeneration"
"actions":
- "desc": "The oni makes two attacks, either with its claws or its glaive."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage."
  "name": "Claw (Oni Form Only)"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d10 + 4) slashing damage, or 9 (1d10 + 4) slashing damage in Small or\
    \ Medium form."
  "name": "Glaive"
- "desc": "The oni magically polymorphs into a Small or Medium humanoid, into a Large\
    \ giant, or back into its true form. Other than its size, its statistics are the\
    \ same in each form. The only equipment that is transformed is its glaive, which\
    \ shrinks so that it can be wielded in humanoid form. If the oni dies, it reverts\
    \ to its true form, and its glaive reverts to its normal size."
  "name": "Change Shape"
"source":
- "MM"
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/giant/token/oni.webp"
```
^statblock

## Environment

forest, urban