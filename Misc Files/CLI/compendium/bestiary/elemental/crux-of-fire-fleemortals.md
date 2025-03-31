---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/artillery
- ttrpg-cli/monster/type/elemental/fire
statblock: inline
aliases: ["Crux of Fire"]
---
# [Crux of Fire](Misc Files\CLI\compendium\bestiary\elemental/crux-of-fire-fleemortals.md)
*Source: Flee, Mortals! p. 89*  

```statblock
"name": "Crux of Fire (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "fire, Artillery"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "9"
- !!int "17"
- !!int "16"
- !!int "11"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "6"
"skillsaves":
  "Perception": !!int "4"
  "Performance": !!int "6"
"damage_resistances": "poison"
"damage_immunities": "fire"
"condition_immunities": "[invisible](Misc%20Files/CLI/rules/conditions.md#Invisible),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Ignan"
"cr": "5"
"traits":
- "desc": "The crux sheds bright light in a 20-foot radius and dim light for an additional\
    \ 20 feet, and they can't benefit from being [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible).\
    \ A creature who starts their turn grappling or [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ by the crux takes 7 (2d6) fire damage."
  "name": "Ablaze"
"actions":
- "desc": "The crux makes two Flame Tongue or two Sulfurous Rake attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage, and the target can't take reactions this turn."
  "name": "Sulfurous Rake"
- "desc": "Ranged Spell Attack: +6 to hit, range 100 ft., one target. Hit: 13\
    \ (2d12) fire damage. If the target is a flammable object that isn't being worn\
    \ or carried, it ignites."
  "name": "Flame Tongue"
"bonus_actions":
- "desc": "The crux imbues the power of fire in themself or another Elemental they\
    \ can see within 30 feet of them, granting one of the following effects of that\
    \ Elemental's choice:\n\n- Flame Bloom. The Elemental launches a seed of flame\
    \ at a point they can see within 60 feet of them. A 10-footradius sphere centered\
    \ on that point erupts with fire and burns for 1 minute. Each creature who enters\
    \ that area for the first time on a turn or starts their turn there takes 10 (3d6)\
    \ fire damage.  \n- Smoke Screen. The Elemental exudes an aura of smoke 10\
    \ feet in every direction for 1 minute or until dispersed by a moderate or stronger\
    \ wind. The smoky area is heavily obscured for all creatures who aren't fire elementals.\
    \  "
  "name": "Convocation of Fire (1/Day)"
- "desc": "The crux gains a flying speed of 30 feet until the end of their turn and\
    \ can move up to their speed."
  "name": "Flame Jet (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Crux%20of%20Fire.png"
```
^statblock