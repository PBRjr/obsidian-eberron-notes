---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/controller
statblock: inline
aliases: ["Anthracia, Princess of Venom"]
---
# [Anthracia, Princess of Venom](Misc Files\CLI\compendium\bestiary\npc/anthracia-princess-of-venom-fleemortals.md)
*Source: Flee, Mortals! p. 369*  

```statblock
"name": "Anthracia, Princess of Venom (FleeMortals)"
"size": "Medium"
"type": "fey"
"subtype": "Controller"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "15"
- !!int "20"
- !!int "22"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "5"
  "Wisdom": !!int "8"
"skillsaves":
  "Nature": !!int "8"
  "Stealth": !!int "8"
  "Perception": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Common, Elvish, Sylvan"
"cr": "5"
"traits":
- "desc": "Anthracia has advantage on saving throws against powers, spells, and other\
    \ supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "Anthracia makes three attacks using Stone Touch, Missile Thorn, or both.\
    \ She can also use Tree Teleport, if available."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +9 to hit, reach 5 ft., one target. Hit: 13 (3d8)\
    \ necrotic damage, and the target must succeed on a DC 17 Constitution saving\
    \ throw or be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained) (save\
    \ ends at end of turn) as their limbs become heavy. If this attack reduces a creature\
    \ to 0 hit points, they become stable and are [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified)\
    \ into a withered stone tree featuring their tortured likeness. The petrification\
    \ lasts until the creature is restored by a cure ailment power of 4th order or\
    \ higher, a [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell, or a similar supernatural effect."
  "name": "Stone Touch"
- "desc": "Ranged Spell Attack: +9 to hit, range 90 ft., one target. Hit: 7\
    \ (2d6) piercing damage plus 7 (2d6) poison damage."
  "name": "Missile Thorn"
- "desc": "Anthracia touches a living tree. She instantly teleports to an unoccupied\
    \ space within 5 feet of another living tree within 500 feet of the first.\n\n\
    Both trees must be Medium or larger."
  "name": "Tree Teleport (3/Day; 5th-Level Spell)"
- "desc": "Anthracia conjures an opaque wall of poisonous gas centered on a point\
    \ she can see within 150 feet of her. The wall can be up to 50 feet long, 15 feet\
    \ high, and 5 feet thick. The wall lingers in the air for 1 minute and its area\
    \ is heavily obscured. Each creature who is in that area when the wall appears\
    \ or who enters it for the first time on a turn must make a DC 17 Constitution\
    \ saving throw, taking 26 (4d12) poison damage on a failed save, or half as\
    \ much damage on a successful one. Creatures who don't need to breathe automatically\
    \ succeed on this saving throw. A moderate wind (at least 10 miles per hour) disperses\
    \ the wall after 4 rounds. A strong wind (at least 20 miles per hour) disperses\
    \ it after 1 round."
  "name": "Wall of Poison (1/Day)"
"reactions":
- "desc": "When an enemy moves within 15 feet of Anthracia, she creates a small tremor\
    \ in the ground beneath her. Each creature within 15 feet of her must succeed\
    \ on a DC 17 Dexterity saving throw or fall [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Sudden Quake"
"source":
- "FleeMortals"
```
^statblock