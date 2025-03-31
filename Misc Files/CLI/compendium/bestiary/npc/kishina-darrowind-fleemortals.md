---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-elf
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
aliases: ["Kishina Darrowind"]
---
# [Kishina Darrowind](Misc Files\CLI\compendium\bestiary\npc/kishina-darrowind-fleemortals.md)
*Source: Flee, Mortals! p. 383*  

```statblock
"name": "Kishina Darrowind (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf, Skirmisher"
"alignment": "Lawful Neutral"
"ac": !!int "19"
"ac_class": "pathfinder's boots"
"hp": !!int "121"
"hit_dice": "22d8 + 22"
"stats":
- !!int "15"
- !!int "24"
- !!int "13"
- !!int "10"
- !!int "24"
- !!int "10"
"speed": "50 ft."
"saves":
  "Dexterity": !!int "10"
  "Wisdom": !!int "10"
  "Strength": !!int "5"
"skillsaves":
  "Athletics": !!int "5"
  "Insight": !!int "10"
  "Perception": !!int "10"
  "Acrobatics": !!int "10"
"senses": "darkvision 60 ft., passive Perception 20"
"languages": "Common, Elvish"
"cr": "6"
"traits":
- "desc": "Kishina has advantage on saving throws she makes to avoid or end the [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ condition on herself."
  "name": "Charm Resistant"
- "desc": "Kishina takes no damage from falling."
  "name": "Light Landing"
- "desc": "Kishina's long jump is up to 45 feet and her high jump is up to 15 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Kishina makes four Unarmed Strike attacks or three Throwing Knife attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 11\
    \ (1d8 + 7) bludgeoning damage, or 20 (3d8 + 7) bludgeoning damage on a critical\
    \ hit."
  "name": "Unarmed Strike"
- "desc": "Ranged Weapon Attack: +10 to hit, range 20/60 ft., one target. Hit:\
    \ 9 (1d4 + 7) piercing damage."
  "name": "Throwing Knife"
- "desc": "Kishina moves up to her speed without provoking opportunity attacks, hitting\
    \ a pressure point on each enemy she can see who she passes within 5 feet of during\
    \ this move. Each target must succeed on a DC 18 Constitution saving throwing\
    \ or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) until the start\
    \ of their next turn. A creature who fails this save by 5 or more also falls [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Painful Sprint (Recharge 6)"
"bonus_actions":
- "desc": "Kishina attempts to throw a Large or smaller enemy she can see within 5\
    \ feet of her. The target must succeed on a DC 18 Dexterity saving throw or be\
    \ moved up to 15 feet away from her and be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Throw"
"reactions":
- "desc": "When Kishina is targeted by an attack or a [magic missile](Misc%20Files/CLI/compendium/spells/magic-missile-xphb.md)\
    \ spell, she conjures an [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ barrier of force. Until the start of her next turn, she gains a +5 bonus to\
    \ AC, including against the triggering attack, and takes no damage from magic\
    \ missile."
  "name": "Shield (3/Day; 1st-Level Spell)"
"source":
- "FleeMortals"
```
^statblock