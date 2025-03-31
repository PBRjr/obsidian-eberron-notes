---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/skirmisher
statblock: inline
aliases: ["Vampire"]
---
# [Vampire](Misc Files\CLI\compendium\bestiary\undead/vampire-fleemortals.md)
*Source: Flee, Mortals! p. 270*  

```statblock
"name": "Vampire (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Skirmisher"
"alignment": "typically  Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"stats":
- !!int "20"
- !!int "20"
- !!int "18"
- !!int "18"
- !!int "16"
- !!int "20"
"speed": "30 ft., fly 30 ft."
"saves":
  "Charisma": !!int "10"
  "Dexterity": !!int "10"
  "Wisdom": !!int "8"
"skillsaves":
  "Intimidation": !!int "10"
  "Deception": !!int "10"
  "Stealth": !!int "10"
  "Insight": !!int "8"
  "Perception": !!int "8"
  "History": !!int "9"
  "Persuasion": !!int "10"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from mundane attacks"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 18"
"languages": "the languages they knew in life"
"cr": "13"
"traits":
- "desc": "In addition to any other spells in this stat block, the vampire can cast\
    \ the following spells, using Charisma as the spellcasting ability (spell save\
    \ DC 18):\n\nAt will: [charm person](Misc%20Files/CLI/compendium/spells/charm-person-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
    \ [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
    \ [disguise self](Misc%20Files/CLI/compendium/spells/disguise-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
    \ [sending](Misc%20Files/CLI/compendium/spells/sending-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
    \n1/day each: [clairvoyance](Misc%20Files/CLI/compendium/spells/clairvoyance-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
    \ [geas](Misc%20Files/CLI/compendium/spells/geas-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
    \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
    \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action (see\
    \ spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "Each time the vampire takes radiant damage, they take an extra 10 radiant\
    \ damage."
  "name": "Radiant Aversion"
- "desc": "When the vampire drops to 0 hit points and is not in sunlight, running\
    \ water, or their resting place, the vampire teleports to their resting place.\
    \ While in their resting place, the vampire is stable. After spending 1 hour in\
    \ their resting place with 0 hit points, they regain 1 hit point."
  "name": "Resting Place"
- "desc": "The vampire has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
"actions":
- "desc": "The vampire makes two Claw attacks and, if possible, a Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage plus 10 (3d6) necrotic damage. If the target is\
    \ Large or smaller, they are [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 18). While [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained).\
    \ Moving while grappling a Medium or smaller creature doesn't halve the vampire's\
    \ speed. A vampire can have only one target [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way at a time."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one creature who is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ by the vampire, [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained). Hit: 8 (1d6\
    \ + 5) piercing damage plus 10 (3d6) necrotic damage. The target's hit point\
    \ maximum is reduced by a number equal to the necrotic damage taken, and the vampire\
    \ regains hit points equal to that number. The reduction lasts until reversed\
    \ by a cure ailment power of 4th order or higher, a [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell, or a similar supernatural effect. The target dies if this attack reduces\
    \ their hit point maximum to 0. A Humanoid slain in this way rises the following\
    \ midnight as a vampire spawn under the vampire's control."
  "name": "Bite"
- "desc": "The vampire, along with anything they are wearing or carrying, turns into\
    \ a cloud of blood-sucking mist. When they do, they release any creature they\
    \ were grappling, and if the vampire was [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained), that effect\
    \ ends for them. Then the vampire flies up to twice their speed to an unoccupied\
    \ space. During this move, the vampire ignores difficult terrain, doesn't provoke\
    \ opportunity attacks, and can move through creatures and objects. Each creature\
    \ the vampire passes through must make a DC 18 Constitution saving throw, taking\
    \ 35 (10d6) necrotic damage on a failed save, or half as much damage on a successful\
    \ one. At the end of this movement, the vampire transforms back into their previous\
    \ form."
  "name": "Exsanguinating Mist (Recharge 6)"
"bonus_actions":
- "desc": "The vampire targets one creature they can see within 30 feet of them and\
    \ who can see them. The target must make a DC 18 Wisdom saving throw. On a failed\
    \ save, the target uses their reaction, if available, to move up to their speed\
    \ to a location chosen by the vampire, then either makes a melee attack against\
    \ a target of the vampire's choice or falls [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ (vampire's choice).\n\nCreatures who can't be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ automatically succeed on this saving throw, and creatures who have advantage\
    \ on saving throws against being [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ make this saving throw with advantage."
  "name": "Beguile"
- "desc": "The vampire moves up to their speed without provoking opportunity attacks."
  "name": "Inhuman Agility"
"reactions":
- "desc": "When an ally the vampire can see takes damage, the vampire can command\
    \ the ally to move up to their speed without provoking opportunity attacks."
  "name": "Run, My Child"
"lair_actions":
- "desc": "When fighting inside their lair, a vampire can take lair actions. On initiative\
    \ count 20 (losing initiative ties), the vampire can take one lair action to cause\
    \ one of the following effects; the vampire can't use the same lair action two\
    \ rounds in a row:"
  "name": ""
- "desc": "- Children of the Night. A swarm of bats and insects flies around the\
    \ vampire, moving with them. The area within 30 feet of the vampire is heavily\
    \ obscured for other creatures until the end of initiative count 20 on the next\
    \ round.  \n- Blood Rain. The vampire chooses a point they can see within\
    \ 60 feet of them. Blood rains down in a 40-foothigh, 10-foot-radius cylinder\
    \ centered on this point until the end of initiative count 20 on the next round.\
    \ When a creature who isn't Undead in the cylinder takes necrotic damage, they\
    \ take an extra 5 (1d10) necrotic damage.  \n- Obey My Desire. The vampire\
    \ exerts their will on those who surround them. Each creature within 60 feet of\
    \ the vampire who can hear them must succeed on a DC 18 Wisdom saving throw or\
    \ be charmed by the vampire until the end of this turn. Each charmed creature\
    \ must immediately use their reaction, if available, to make a melee attack against\
    \ another creature, to make a melee attack against themself, or to drop [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ (vampire's choice).  "
  "name": ""
"source":
- "FleeMortals"
```
^statblock