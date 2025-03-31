---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/soldier
statblock: inline
aliases: ["Wight"]
---
# [Wight](Misc Files\CLI\compendium\bestiary\undead/wight-fleemortals.md)
*Source: Flee, Mortals! p. 255*  

```statblock
"name": "Wight (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Soldier"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "16"
- !!int "13"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Perception": !!int "3"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages they knew in life"
"cr": "3"
"actions":
- "desc": "The wight makes one Longsword attack and one Vitality Theft attack, or\
    \ they make two Heavy Crossbow attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. Hit:\
    \ 6 (1d10 + 1) piercing damage."
  "name": "Heavy Crossbow"
- "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one creature. Hit: 9\
    \ (2d8) necrotic damage, and the wight regains a number of hit points equal\
    \ to half the damage dealt. Until the start of the wight's next turn, the target\
    \ has disadvantage on attack rolls made against creatures other than the wight."
  "name": "Vitality Theft"
"reactions":
- "desc": "When an ally the wight can see within 5 feet of them is hit by an attack,\
    \ the wight forces the attacker to reroll the attack and to instead target the\
    \ wight or a willing ally within 5 feet of the original target."
  "name": "Decaying Guard"
"source":
- "FleeMortals"
```
^statblock