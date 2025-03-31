---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
aliases: ["Blink Dog"]
---
# [Blink Dog](Misc Files\CLI\compendium\bestiary\fey/blink-dog.md)
*Source: Monster Manual p. 318, Eberron: Rising from the Last War. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

A blink dog takes its name from its ability to blink in and out of existence, a talent it uses to aid its attacks and to avoid harm. Blink dogs harbor a long-standing hatred for displacer beasts and attack them on sight.

```statblock
"name": "Blink Dog"
"size": "Medium"
"type": "fey"
"alignment": "Lawful Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "12"
- !!int "17"
- !!int "12"
- !!int "10"
- !!int "13"
- !!int "11"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "Blink Dog, understands Sylvan but can't speak it"
"cr": "1/4"
"traits":
- "desc": "The dog has advantage on Wisdom ([Perception](Misc%20Files/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage."
  "name": "Bite"
- "desc": "The dog magically teleports, along with any equipment it is wearing or\
    \ carrying, up to 40 feet to an unoccupied space it can see. Before or after teleporting,\
    \ the dog can make one bite attack."
  "name": "Teleport (Recharge 4-6)"
"source":
- "MM"
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/fey/token/blink-dog.webp"
```
^statblock

## Environment

forest