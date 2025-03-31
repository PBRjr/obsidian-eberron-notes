---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/elemental/air
- ttrpg-cli/monster/type/elemental/artillery
- ttrpg-cli/monster/type/elemental/water
statblock: inline
aliases: ["Oracle of Storms"]
---
# [Oracle of Storms](Misc Files\CLI\compendium\bestiary\elemental/oracle-of-storms-fleemortals.md)
*Source: Flee, Mortals! p. 97*  

```statblock
"name": "Oracle of Storms (FleeMortals)"
"size": "Huge"
"type": "elemental"
"subtype": "air, water, Artillery"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "189"
"hit_dice": "18d12 + 72"
"stats":
- !!int "17"
- !!int "21"
- !!int "18"
- !!int "12"
- !!int "18"
- !!int "17"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "10"
"skillsaves":
  "Nature": !!int "11"
  "Perception": !!int "9"
  "History": !!int "11"
  "Performance": !!int "8"
"damage_immunities": "lightning, poison, thunder"
"condition_immunities": "[dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled),\
  \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned), [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
  \ [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)"
"senses": "blindsight 60 ft., passive Perception 19"
"languages": "Aquan, Auran, Common"
"cr": "16"
"traits":
- "desc": "In addition to any other spells in this stat block, the oracle can cast\
    \ the following spells, using Wisdom as the spellcasting ability (spell save DC\
    \ 17):\n\n3/day each: [commune](Misc%20Files/CLI/compendium/spells/commune-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
    \ [commune with nature](Misc%20Files/CLI/compendium/spells/commune-with-nature-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
    \ [legend lore](Misc%20Files/CLI/compendium/spells/legend-lore-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
    \ [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
    \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
    \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action (see\
    \ spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "When the oracle starts their turn outdoors while not [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ they can stoke a thunderstorm (no action required). For 1 minute or until the\
    \ oracle uses Turbulent Escalation again, the weather in a 1-mile radius centered\
    \ on the oracle changes as follows:\n\n- If the sky is cloudless, it becomes cloudy.\
    \  \n- If the sky is cloudy, it begins to rain or snow (oracle's choice).  \n\
    - If it's raining or snowing, the weather becomes stormy.  "
  "name": "Turbulent Escalation"
"actions":
- "desc": "The oracle uses Tempest Bolt twice. They can replace one use with a Cyclone\
    \ Staff attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 23\
    \ (4d8 + 5) bludgeoning damage plus 22 (4d10) thunder damage, and the oracle\
    \ moves the target up to 10 feet in any direction."
  "name": "Cyclone Staff"
- "desc": "A bolt of lightning streaks from the oracle to strike one creature they\
    \ can see within 90 feet of them, or within 300 feet of them if the target is\
    \ outdoors and the weather is stormy. The target must make a DC 18 Dexterity saving\
    \ throw, taking 31 (7d8) lightning damage on a failed save, or half as much\
    \ damage on a successful one. If the target is outdoors and the weather is stormy,\
    \ they have disadvantage on the saving throw."
  "name": "Tempest Bolt"
"bonus_actions":
- "desc": "The oracle imbues the power of storm in themself or another Elemental they\
    \ can see within 30 feet of them, granting one of the following effects of that\
    \ Elemental's choice:\n\n- Lightning Within. The Elemental becomes charged\
    \ with lightning. The next time the Elemental hits a target with an attack within\
    \ the next minute, the attack deals an extra 33 (6d10) lightning damage.  \n\
    - Thunder Burst. A concussive shock wave erupts from the Elemental toward\
    \ four creatures they can see within 60 feet of them. Each target must succeed\
    \ on a DC 17 Constitution saving throw or take 22 (4d10) thunder damage, be\
    \ pushed up to 10 feet away from the Elemental, and be [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened)\
    \ until the end of the target's next turn.  "
  "name": "Convocation of Storms (2/Day)"
"source":
- "FleeMortals"
```
^statblock