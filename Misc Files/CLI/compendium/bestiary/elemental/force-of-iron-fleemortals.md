---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/brute
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/fire
statblock: inline
aliases: ["Force of Iron"]
---
# [Force of Iron](Misc Files\CLI\compendium\bestiary\elemental/force-of-iron-fleemortals.md)
*Source: Flee, Mortals! p. 96*  

```statblock
"name": "Force of Iron (FleeMortals)"
"size": "Large"
"type": "elemental"
"subtype": "earth, fire, Brute"
"alignment": "Any alignment"
"ac": !!int "19"
"ac_class": "natural armor; 22 in Shield Form"
"hp": !!int "150"
"hit_dice": "12d10 + 84"
"stats":
- !!int "21"
- !!int "10"
- !!int "25"
- !!int "11"
- !!int "13"
- !!int "12"
"speed": "60 ft."
"saves":
  "Strength": !!int "9"
"skillsaves":
  "Athletics": !!int "9"
  "Perception": !!int "5"
"damage_resistances": "fire"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened), [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 15"
"languages": "Common, Ignan, Terran"
"cr": "10"
"actions":
- "desc": "The force of iron uses Form Stance then makes three Ferrous Blade attacks\
    \ or three Iron Spike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft. (20 ft. in Polearm Form),\
    \ one target. Hit: 19 (4d6 + 5) slashing damage."
  "name": "Ferrous Greatblade"
- "desc": "Ranged Weapon Attack: +9 to hit, range 30/60 ft., one target. Hit:\
    \ 14 (2d8 + 5) piercing damage."
  "name": "Iron Spike"
- "desc": "The force of iron shapes their body to gain one of the following benefits\
    \ until the start of their next turn:"
  "name": "Form Stance"
- "desc": "The force of iron's melee attacks have a reach of 20 feet instead of 5\
    \ feet."
  "name": "Polearm Form"
- "desc": "The force of iron has advantage on all melee attack rolls, but attack rolls\
    \ against the force of iron have advantage."
  "name": "Reckless Form"
- "desc": "The force of iron gains a +3 bonus to AC."
  "name": "Shield Form"
- "desc": "The force of iron's attacks deal an extra 13 (2d12) fire damage on a\
    \ hit."
  "name": "Fire Form (1/Day)"
"bonus_actions":
- "desc": "The force of iron imbues the power of iron in themself or another Elemental\
    \ they can see within 30 feet of them, granting one of the following effects of\
    \ that Elemental's choice:\n\n- Earth Reinforcements. Five [earth spark](Misc%20Files/CLI/compendium/bestiary/elemental/earth-spark-fleemortals.md)s\
    \ appear in unoccupied spaces within 20 feet of the Elemental. The sparks understand\
    \ the Elemental, follow their verbal commands, and act immediately after the Elemental\
    \ in the initiative order.  \n- Iron Skin. Metal covers the Elemental, granting\
    \ them resistance to bludgeoning, piercing, and slashing damage for 1 minute or\
    \ until their [concentration](Misc%20Files/CLI/rules/conditions.md#Concentration)\
    \ is broken (as if [concentrating](Misc%20Files/CLI/rules/conditions.md#Concentration)\
    \ on a spell).  "
  "name": "Convocation of Iron (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Force%20of%20Iron.png"
```
^statblock