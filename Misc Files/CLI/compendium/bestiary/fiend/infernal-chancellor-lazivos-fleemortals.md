---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
- ttrpg-cli/monster/type/fiend/leader
statblock: inline
aliases: ["Infernal Chancellor Lazivos"]
---
# [Infernal Chancellor Lazivos](Misc Files\CLI\compendium\bestiary\fiend/infernal-chancellor-lazivos-fleemortals.md)
*Source: Flee, Mortals! p. 71*  

```statblock
"name": "Infernal Chancellor Lazivos (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Leader"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "238"
"hit_dice": "28d8 + 112"
"stats":
- !!int "14"
- !!int "20"
- !!int "18"
- !!int "19"
- !!int "18"
- !!int "24"
"speed": "40 ft., fly 60 ft."
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "10"
  "Wisdom": !!int "9"
  "Intelligence": !!int "9"
"skillsaves":
  "Deception": !!int "12"
  "Religion": !!int "9"
  "Insight": !!int "9"
  "Perception": !!int "9"
  "Arcana": !!int "9"
  "Persuasion": !!int "12"
"damage_resistances": "psychic; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "fire"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), [exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [flanked](Misc%20Files/CLI/rules/conditions.md#Flanked), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "Common, Infernal"
"cr": "16"
"traits":
- "desc": "When Lazivos fails a saving throw, he can succeed instead. When he does,\
    \ his speed is halved and he can't take bonus actions or reactions until the end\
    \ of his next turn."
  "name": "Security for Speed (3/Day)"
- "desc": "Lazivos has advantage on saving throws against powers, spells, and other\
    \ supernatural effects."
  "name": "Supernatural Resistance"
- "desc": "If a creature Lazivos can hear within 60 feet of him speaks his true name\
    \ aloud, Lazivos loses his damage resistances, damage immunities, and Devilish\
    \ Charm reaction for 24 hours. Lazivos's true name is Minto Abi."
  "name": "True Name"
"actions":
- "desc": "Lazivos makes three attacks using Infernal Rapier, Chancellor's Decree,\
    \ or both."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 9\
    \ (1d8 + 5) piercing damage plus 9 (2d8) fire damage, and the target is marked\
    \ with an infernal sigil until the end of their next turn. While marked, a creature\
    \ can't hide or benefit from being [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible),\
    \ and attack rolls against them have advantage."
  "name": "Infernal Rapier"
- "desc": "Ranged Spell Attack: +12 to hit, range 120 ft., one target. Hit:\
    \ 18 (2d10 + 7) psychic damage, and the target must make a DC 20 Wisdom saving\
    \ throw. On a failed save, the target is [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by Lazivos until the end of his next turn or until Lazivos or one of his allies\
    \ harms the target."
  "name": "Chancellor's Decree"
- "desc": "Lazivos commands the attention of each enemy within 30 feet of him who\
    \ can hear him. Each target must make a DC 20 Wisdom saving throw. On a failed\
    \ save, a creature must choose to either take 27 (6d8) fire damage plus 27 (6d8)\
    \ psychic damage or be [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed) for\
    \ 1 minute (save ends at end of turn). On a successful save, a creature must either\
    \ choose to take half as much damage or be [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed)\
    \ until the end of their next turn. Succeed or fail, if a creature is already\
    \ [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed), they must choose the damage"
  "name": "Diabolic Deposition (Recharge 5-6)"
"bonus_actions":
- "desc": "Lazivos commands a creature [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by him to use their reaction, if available, to make a weapon attack against\
    \ a target of his choice."
  "name": "As I Say"
"reactions":
- "desc": "When Lazivos is targeted by an attack, power, spell, or other supernatural\
    \ effect by a creature he can see within 60 feet of him, the creature must make\
    \ a DC 20 Charisma saving throw. On a failed save, the creature is [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by Lazivos until the start of the creature's next turn, and Lazivos chooses\
    \ a new target he can see for the triggering effect. The new target must be within\
    \ the triggering effect's range."
  "name": "Devilish Charm"
"legendary_actions":
- "desc": "Lazivos has three villain actions. He can take each action once during\
    \ an encounter after an enemy's turn. He can take these actions in any order but\
    \ can use only one per round."
  "name": ""
- "desc": "Lazivos invokes an infernal word of power. Up to three enemies within 60\
    \ feet of him who can hear him must make a DC 20 Charisma saving throw. On a failed\
    \ save, a target is [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed) by\
    \ Lazivos for 1 hour (save ends at end of turn) or until Lazivos or one of his\
    \ allies harms the target. On a successful save, a target takes 16 (3d10) psychic\
    \ damage."
  "name": "Action 1: Welcome, Friends"
- "desc": "Lazivos and each ally within 60 feet of him moves up to their speed without\
    \ provoking opportunity attacks. Each creature [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by Lazivos moves up to half their speed in a direction he chooses (no action\
    \ required)."
  "name": "Action 2: Heed My Commands!"
- "desc": "Lazivos switches places with a willing creature of his choice within 120\
    \ feet of him. Immediately afterward, up to five creatures of Lazivos's choice\
    \ within 120 feet of him can make a melee attack (no action required)."
  "name": "Action 3: Deceptive Stratagem"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Infernal%20Chancellor%20Lazivos.png"
```
^statblock