---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/retainer
- ttrpg-cli/monster/type/undead/undead
statblock: inline
aliases: ["Ghost Sycophant"]
---
# [Ghost Sycophant](Misc Files\CLI\compendium\bestiary\undead/ghost-sycophant-fleemortals.md)
*Source: Flee, Mortals! p. 250*  

```statblock
"name": "Ghost Sycophant (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "undead, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"stats":
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "16"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Intimidation": !!int "0"
  "Stealth": !!int "0"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"damage_immunities": "necrotic"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, any two languages they knew in life"
"actions":
- "desc": "Melee or Ranged Spell Attack: +3 plus PB to hit, reach 5 ft. or range\
    \ 60 ft., one target. Hit: 5 (1d10) necrotic damage. This spell's damage increases\
    \ by 1d10 when the sycophant reaches 5th level (2d10), 11th level (3d10),\
    \ and 17th level (4d10)."
  "name": "Signature Attack (Dark Essence)"
- "desc": "When the sycophant hits a creature with a signature attack, the target\
    \ must also succeed on a DC 10 plus PB Wisdom saving throw or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of the sycophant for 1 minute (save ends at end of turn)."
  "name": "3rd Level: Call of the Dead (3/Day)"
- "desc": "As an action, the sycophant becomes [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ for 1 minute or until they use a bonus action to end this effect. While [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible),\
    \ the sycophant can move through creatures and objects as if they were difficult\
    \ terrain, and the sycophant's signature attacks deal an extra PB damage to creatures\
    \ who can't see them. The sycophant takes 5 (1d10) force damage if they end\
    \ their turn inside an object."
  "name": "5th Level: Astral Presence (3/Day)"
- "desc": "As an action, the sycophant chooses up to PB creatures they can see within\
    \ 30 feet of them. Each target must succeed on a DC 10 plus PB Charisma saving\
    \ throw or make an attack against their nearest ally (no action required). A [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ creature has disadvantage on the saving throw."
  "name": "7th Level: Whispers of the Dead (3/Day)"
"source":
- "FleeMortals"
```
^statblock