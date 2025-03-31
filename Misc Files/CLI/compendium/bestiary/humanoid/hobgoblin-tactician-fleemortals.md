---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
aliases: ["Hobgoblin Tactician"]
---
# [Hobgoblin Tactician](Misc Files\CLI\compendium\bestiary\humanoid/hobgoblin-tactician-fleemortals.md)
*Source: Flee, Mortals! p. 157*  

```statblock
"name": "Hobgoblin Tactician (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "History": !!int "0"
  "Arcana": !!int "0"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin, Infernal"
"actions":
- "desc": "Melee or Ranged Spell Attack: +3 plus PB to hit, reach 5 ft. or range\
    \ 60 ft., one target. Hit: 5 (1d10) fire damage. A flammable object hit by\
    \ this spell ignites if it isn't being worn or carried. This spell's damage increases\
    \ by 1d10 when the tactician reaches 5th level (2d10), 11th level (3d10),\
    \ and 17th level (4d10)."
  "name": "Signature Attack (Flame Touch)"
- "desc": "As an action, the tactician makes a signature attack but doesn't make an\
    \ attack roll for it. Instead, the attack automatically hits, and each ally within\
    \ 30 feet of the target can use their reaction to move up to their speed toward\
    \ the target."
  "name": "3rd Level: Heat Seeker (3/Day)"
- "desc": "When the tactician hits with a signature attack, each creature within 5\
    \ feet of the target can use a reaction to make a melee weapon attack against\
    \ the target."
  "name": "5th Level: Beacon (3/Day)"
- "desc": "As an action, the tactician hurls a ball of fire at a point they can see\
    \ within 120 feet of them. The ball explodes in a 20-foot-radius sphere, forcing\
    \ each enemy in that area to make a DC 10 plus PB Dexterity saving throw. On a\
    \ failed save, a creature takes PBd12 fire damage and is pushed 20 feet away\
    \ from the center of the area. On a successful save, a creature takes half as\
    \ much damage and isn't pushed. The fire spreads around corners and ignites flammable\
    \ objects in the area that aren't being worn or carried."
  "name": "7th Level: Explosion (1/Day)"
"source":
- "FleeMortals"
```
^statblock