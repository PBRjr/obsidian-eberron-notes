---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/skirmisher
statblock: inline
aliases: ["Klar"]
---
# [Klar](Misc Files\CLI\compendium\bestiary\npc/klar-fleemortals.md)
*Source: Flee, Mortals! p. 359*  

```statblock
"name": "Klar (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Skirmisher"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"stats":
- !!int "18"
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "16"
"speed": "40 ft., swim 30 ft."
"saves":
  "Strength": !!int "6"
  "Constitution": !!int "5"
"skillsaves":
  "Athletics": !!int "6"
  "Deception": !!int "5"
  "Survival": !!int "5"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "Klar can breathe air and water."
  "name": "Amphibious"
- "desc": "Klar can mimic animal sounds. A creature who hears the sounds can tell\
    \ they are imitations with a successful DC 13 Wisdom ([Insight](Misc%20Files/CLI/rules/skills.md#Insight))\
    \ check."
  "name": "Mimicry"
- "desc": "Klar's long jump is up to 40 feet and their high jump is up to 15 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Klar makes one Bite attack and one Mantis Claws attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 f., one target. Hit: 7 (1d6\
    \ + 4) slashing damage. If the target is Medium or smaller, they are [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 14). While [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained).\
    \ Moving while grappling a Medium or smaller target doesn't halve Klar's speed.\
    \ Klar can have only one target [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way at a time."
  "name": "Mantis Claws"
"bonus_actions":
- "desc": "Klar lets loose a terrifying roar.\n\nEach creature within 30 feet of Klar\
    \ who can hear them must succeed on a DC 13 Wisdom saving throw or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of Klar for 1 minute. If a creature [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ in this way takes damage, they can repeat this saving throw, ending the effect\
    \ on themself on a success."
  "name": "Bellowing Roar (1/Day)"
- "desc": "Klar jumps up to half their speed without provoking opportunity attacks."
  "name": "Kangaroo Leap"
"source":
- "FleeMortals"
```
^statblock