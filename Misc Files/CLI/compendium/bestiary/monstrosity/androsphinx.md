---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
aliases: ["Androsphinx"]
---
# [Androsphinx](Misc Files\CLI\compendium\bestiary\monstrosity/androsphinx.md)
*Source: Monster Manual p. 281. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

An androsphinx bears the head of a humanoid male on its lion's body. Outwardly gruff and downcast, it often begins conversations with insults or negative observations. Beneath this gruff exterior, however, an androsphinx has a noble heart. It has no wish to lie or deceive, but it doesn't give away information readily, choosing its words as wisely as it guards its secrets.

An androsphinx tests the courage and valor of supplicants, not only by forcing them to complete quests but also with its terrible roar, which echoes for miles as it terrifies and deafens nearby creatures. Those who pass its tests may be rewarded with a heroes' feast.

## Sphinxes

In sacred isolation, a sphinx guards the secrets and treasures of the gods. As it calmly regards each new party that comes before it, the bones of supplicants and quest seekers that failed to pass its tests lie scattered around its lair. Its great wings sweep along its flanks, its tawny leonine body rippling with muscle and possessed of forepaws powerful enough to tear a humanoid in half.

### Divine Guardians

Sphinxes test the worth of those who seek the treasures of the gods, whether forgotten secrets or mighty spells, artifacts or magical gateways. Creatures that choose to face a sphinx's test are bound to that test unto death, and only those worthy will survive it. The rest the sphinx destroys.

Some sphinxes are high priests of the gods that create them, but most are simply embodied spirits, brought into the mortal realm by devout prayer or direct intervention. A sphinx maintains its vigil tirelessly, not needing to sleep or eat. It rarely engages with others of its kind, knowing no other life except its sacred mission.

### Magical Tests

The secrets and treasures a sphinx guards remain under divine protection, so that when a creature fails a sphinx's test, the path to the object or knowledge it guards vanishes. Even if a sphinx is attacked and defeated, a quester will still fail to gain the secret it sought-and will make an enemy of the god that placed the sphinx as a guardian.

Benign deities sometimes grant a sphinx the power to remove supplicants that fail their tests, transporting them away and ensuring that they never encounter the sphinx again. However, those who fail a sphinx's test typically meet a gruesome end beneath its claws.

### Extraplanar Beings

Mortals that encounter sphinxes do so most often in ancient tombs and ruins, but some sphinxes can access extraplanar realms. A conversation with a sphinx that begins between tumbled stone walls might suddenly shift to an alien locale, such as a life-sized game board or a daunting cliff that must be climbed in a howling storm. Sometimes a sphinx must be summoned from such an extradimensional space, with supplicants calling it from its empty lair. Only those the sphinx deems worthy gain admittance to its realm.

### Fallen Sphinxes

Whether through the weariness of the ages, regret at the slaughter of innocents, or dreams of worship by supplicants that attempt to bargain their way to knowledge, some sphinxes break free of their divine command. However, even if a sphinx's alignment and loyalties drift in this way, it never leaves the place it guards or grants its secrets to any except creatures it deems worthy.

> [!quote] A quote from Riddle of the gynosphinx of White Plume Mountain  
> 
> Round she is, yet flat as a board
> 
> Altar of the Lupine Lords
> 
> Jewel on black velvet, pearl in the sea
> 
> Unchanged but e'erchanging, eternally.

### A Sphinx's Lair

A sphinx presides over an ancient temple, sepulcher, or vault, within which are hidden divine secrets and treasures beyond the reach of mortals.

```statblock
"name": "Androsphinx"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "199"
"hit_dice": "19d10 + 95"
"stats":
- !!int "22"
- !!int "10"
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "23"
"speed": "40 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "10"
  "Intelligence": !!int "9"
  "Constitution": !!int "11"
"skillsaves":
  "Religion": !!int "15"
  "Perception": !!int "10"
  "Arcana": !!int "9"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 20"
"languages": "Common, Sphinx"
"cr": "17"
"traits":
- "desc": "The sphinx is a 12th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 18, +10 to hit with spell attacks). It requires no material\
    \ components to cast its spells. The sphinx has the following cleric spells prepared:\n\
    \nCantrips (at will): [sacred flame](Misc%20Files/CLI/compendium/spells/sacred-flame-xphb.md),\
    \ [spare the dying](Misc%20Files/CLI/compendium/spells/spare-the-dying-xphb.md),\
    \ [thaumaturgy](Misc%20Files/CLI/compendium/spells/thaumaturgy-xphb.md)\n\n1st\
    \ level (4 slots): [command](Misc%20Files/CLI/compendium/spells/command-xphb.md),\
    \ [detect evil and good](Misc%20Files/CLI/compendium/spells/detect-evil-and-good-xphb.md),\
    \ [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md)\n\n\
    2nd level (3 slots): [lesser restoration](Misc%20Files/CLI/compendium/spells/lesser-restoration-xphb.md),\
    \ [zone of truth](Misc%20Files/CLI/compendium/spells/zone-of-truth-xphb.md)\n\n\
    3rd level (3 slots): [dispel magic](Misc%20Files/CLI/compendium/spells/dispel-magic-xphb.md),\
    \ [tongues](Misc%20Files/CLI/compendium/spells/tongues-xphb.md)\n\n4th level\
    \ (3 slots): [banishment](Misc%20Files/CLI/compendium/spells/banishment-xphb.md),\
    \ [freedom of movement](Misc%20Files/CLI/compendium/spells/freedom-of-movement-xphb.md)\n\
    \n5th level (2 slots): [flame strike](Misc%20Files/CLI/compendium/spells/flame-strike-xphb.md),\
    \ [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\n\
    \n6th level (1 slots): [heroes' feast](Misc%20Files/CLI/compendium/spells/heroes-feast-xphb.md)"
  "name": "Spellcasting"
- "desc": "The sphinx is immune to any effect that would sense its emotions or read\
    \ its thoughts, as well as any divination spell that it refuses. Wisdom ([Insight](Misc%20Files/CLI/rules/skills.md#Insight))\
    \ checks made to ascertain the sphinx's intentions or sincerity have disadvantage."
  "name": "Inscrutable"
- "desc": "The sphinx's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The sphinx makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d10 + 6) slashing damage."
  "name": "Claw"
- "desc": "The sphinx emits a magical roar. Each time it roars before finishing a\
    \ long rest, the roar is louder and the effect is different, as detailed below.\
    \ Each creature within 500 feet of the sphinx and able to hear the roar must make\
    \ a saving throw.\n\n- First Roar. Each creature that fails a DC 18 Wisdom\
    \ saving throw is [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ for 1 minute. A [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success.  \n- Second Roar. Each creature that\
    \ fails a DC 18 Wisdom saving throw is [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened)\
    \ and [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened) for 1 minute.\
    \ A [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened) creature is\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed) and can repeat the\
    \ saving throw at the end of each of its turns, ending the effect on itself on\
    \ a success.  \n- Third Roar. Each creature makes a DC 18 Constitution saving\
    \ throw. On a failed save, a creature takes 44 (8d10) thunder damage and is\
    \ knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone). On a successful\
    \ save, the creature takes half as much damage and isn't knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone).\
    \  "
  "name": "Roar (3/Day)"
"legendary_actions":
- "desc": "The sphinx makes one claw attack."
  "name": "Claw Attack"
- "desc": "The sphinx magically teleports, along with any equipment it is wearing\
    \ or carrying, up to 120 feet to an unoccupied space it can see."
  "name": "Teleport (Costs 2 Actions)"
- "desc": "The sphinx casts a spell from its list of prepared spells, using a spell\
    \ slot as normal."
  "name": "Cast a Spell (Costs 3 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the sphinx can take a\
    \ lair action to cause one of the following magical effects; the sphinx can't\
    \ use an effect again until it finishes a short or long rest:"
  "name": ""
- "desc": "- The flow of time is altered such that every creature in the lair must\
    \ reroll initiative. The sphinx can choose not to reroll.  \n- The effects of\
    \ time are altered such that every creature in the lair must succeed on a DC 15\
    \ Constitution saving throw or become d20 years older or younger (the sphinx's\
    \ choice), but never any younger than 1 year old. A [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell can restore a creature's age to normal.  \n- The flow of time within the\
    \ lair is altered such that everything within moves up to 10 years forward or\
    \ backward (sphinx's choice). Only the sphinx is immediately aware of the time\
    \ change. A [wish](Misc%20Files/CLI/compendium/spells/wish-xphb.md) spell can\
    \ return the caster and up to seven other creatures designated by the caster to\
    \ their normal time.  \n- The sphinx shifts itself and up to seven other creatures\
    \ it can see within in its lair to another plane of existence. Once outside its\
    \ lair, the sphinx can't use lair actions, but it can return to its lair as a\
    \ bonus action on its turn, taking up to seven creatures with it.  "
  "name": ""
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/monstrosity/token/androsphinx.webp"
```
^statblock

## Environment

desert