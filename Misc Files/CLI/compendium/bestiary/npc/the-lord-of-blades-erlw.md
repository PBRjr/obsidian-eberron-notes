---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/erlw
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/warforged
statblock: inline
aliases: ["The Lord of Blades"]
---
# [The Lord of Blades](Misc Files\CLI\compendium\bestiary\npc/the-lord-of-blades-erlw.md)
*Source: Eberron: Rising from the Last War p. 300*  

The Lord of Blades is a warforged warlord who has broken all ties with his former masters. He has established a nation for his people deep in the Mournland, centered in a great fortress where warforged from all over Khorvaire can come and feel a sense of belonging. No one knows what the Lord of Blades plans for his followers, but many fear that he intends to build a legion of warforged zealots, primed to march from the Mournland to unleash destruction on their former masters.

Some tales assert that the Lord of Blades led the warforged armies of Cyre in the Last War. Others cast him as a newer warforged, perhaps the last to come out of the Cannith creation forges before the Thronehold Accords led to their dismantling. One story claims the Lord of Blades caused the destruction of Cyre and warns that he plans to repeat the Day of Mourning in each of the remaining Five Nations. Whatever the truth, he has become a beacon for warforged everywhere.

## Warforged Nature

The Lord of Blades doesn't require air, food, drink, or sleep.

```statblock
"name": "The Lord of Blades (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "warforged"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "23d8 + 92"
"stats":
- !!int "20"
- !!int "15"
- !!int "18"
- !!int "19"
- !!int "17"
- !!int "18"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "9"
  "Intelligence": !!int "10"
  "Strength": !!int "11"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "11"
  "Perception": !!int "9"
  "History": !!int "10"
  "Arcana": !!int "10"
"damage_resistances": "necrotic, poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ disease"
"senses": "passive Perception 19"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "18"
"traits":
- "desc": "The Lord of Blades is a 20th-level spellcaster. His spellcasting ability\
    \ is Intelligence (spell save DC 18, +10 to hit with spell attacks). He has\
    \ the following artificer spells prepared:\n\nCantrips (at will): [fire bolt](Misc%20Files/CLI/compendium/spells/fire-bolt-xphb.md)\
    \ (see \"Actions\" below), [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md),\
    \ [mending](Misc%20Files/CLI/compendium/spells/mending-xphb.md), [prestidigitation](Misc%20Files/CLI/compendium/spells/prestidigitation-xphb.md)\n\
    \n1st level (4 slots): [expeditious retreat](Misc%20Files/CLI/compendium/spells/expeditious-retreat-xphb.md),\
    \ [sanctuary](Misc%20Files/CLI/compendium/spells/sanctuary-xphb.md), [thunderwave](Misc%20Files/CLI/compendium/spells/thunderwave-xphb.md)\n\
    \n2nd level (3 slots): [blur](Misc%20Files/CLI/compendium/spells/blur-xphb.md),\
    \ [heat metal](Misc%20Files/CLI/compendium/spells/heat-metal-xphb.md), [scorching\
    \ ray](Misc%20Files/CLI/compendium/spells/scorching-ray-xphb.md), [see invisibility](Misc%20Files/CLI/compendium/spells/see-invisibility-xphb.md)\n\
    \n3rd level (3 slots): [dispel magic](Misc%20Files/CLI/compendium/spells/dispel-magic-xphb.md),\
    \ [fly](Misc%20Files/CLI/compendium/spells/fly-xphb.md), [haste](Misc%20Files/CLI/compendium/spells/haste-xphb.md)\n\
    \n4th level (3 slots): [freedom of movement](Misc%20Files/CLI/compendium/spells/freedom-of-movement-xphb.md),\
    \ [Mordenkainen's faithful hound](Misc%20Files/CLI/compendium/spells/mordenkainens-faithful-hound-xphb.md)\n\
    \n5th level (2 slots): [animate objects](Misc%20Files/CLI/compendium/spells/animate-objects-xphb.md),\
    \ [wall of force](Misc%20Files/CLI/compendium/spells/wall-of-force-xphb.md)"
  "name": "Spellcasting"
- "desc": "Any critical hit against the Lord of Blades becomes a normal hit."
  "name": "Adamantine Plating"
- "desc": "A creature that grapples the Lord of Blades or is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ by him takes 13 (3d8) slashing damage. A creature takes 13 (3d8) slashing\
    \ damage if it starts its turn grappling or being [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ by the Lord of Blades."
  "name": "Bladed Armor"
- "desc": "If the Lord of Blades moves at least 10 feet straight toward a target and\
    \ then hits it with his adamantine sixblade on the same turn, the target takes\
    \ an extra 11 (2d10) slashing damage. If the target is a creature, it must succeed\
    \ on a DC 19 Strength saving throw or be pushed up to 10 feet away and knocked\
    \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Charge"
- "desc": "The Lord of Blades has advantage on saving throws against being [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned),\
    \ is immune to disease, and magic can't put him to sleep."
  "name": "Warforged Resilience"
"actions":
- "desc": "The Lord of Blades makes three attacks: two with his adamantine sixblade\
    \ and one with his bladed wings."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 21\
    \ (3d10 + 5) slashing damage plus 7 (2d6) force damage."
  "name": "Adamantine Sixblade"
- "desc": "Melee or Ranged Weapon Attack: +11 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 8 (1d6 + 5) slashing damage."
  "name": "Bladed Wings"
- "desc": "Ranged Spell Attack: +10 to hit, range 120 ft., one target. Hit:\
    \ 22 (4d10) fire damage."
  "name": "Fire Bolt (Cantrip)"
"legendary_actions":
- "desc": "The Lord of Blades makes one weapon attack."
  "name": "Attack"
- "desc": "The Lord of Blades casts one of his cantrips."
  "name": "Cantrip"
- "desc": "The Lord of Blades casts a spell of 2nd level or lower from his spell list\
    \ that takes 1 action to cast."
  "name": "Cast a Spell (Costs 2 Actions)"
- "desc": "The Lord of Blades moves up to his speed without provoking opportunity\
    \ attacks, then makes one attack with his adamantine sixblade. He can make one\
    \ bladed wings attack against each creature he moves past."
  "name": "Blade Dash (Costs 3 Actions)"
"source":
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/npc/token/the-lord-of-blades-erlw.webp"
```
^statblock