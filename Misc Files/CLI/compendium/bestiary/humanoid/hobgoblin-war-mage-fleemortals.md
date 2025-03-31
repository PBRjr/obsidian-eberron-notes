---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/controller
- ttrpg-cli/monster/type/humanoid/hobgoblin
statblock: inline
aliases: ["Hobgoblin War Mage"]
---
# [Hobgoblin War Mage](Misc Files\CLI\compendium\bestiary\humanoid/hobgoblin-war-mage-fleemortals.md)
*Source: Flee, Mortals! p. 153*  

```statblock
"name": "Hobgoblin War Mage (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Controller"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[chain shirt](Misc%20Files/CLI/compendium/items/chain-shirt-xphb.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "10"
- !!int "15"
- !!int "15"
- !!int "18"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin, Infernal"
"cr": "3"
"traits":
- "desc": "When the mage dies, their corpse unleashes a spray of burning orange ichor.\
    \ Each creature within 5 feet of the mage takes 5 fire damage."
  "name": "Infernal Ichor"
"actions":
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 11 (2d10)\
    \ necrotic damage, and if the target is a creature, they must succeed on a DC\
    \ 14 Charisma saving throw or be teleported up to 15 feet to an unoccupied space\
    \ the mage can see."
  "name": "Infernal Teleport"
- "desc": "The mage rains fire down on a point they can see within 60 feet of them.\
    \ Each creature in a 10-foot-radius sphere centered on that point must make a\
    \ DC 14 Dexterity saving throw, taking 10 (3d6) fire damage on a failed save,\
    \ or half as much damage on a successful one. The fire spreads around corners,\
    \ and it ignites flammable objects in that area that aren't being worn or carried."
  "name": "Rain Hellfire (2nd-Level Spell)"
- "desc": "The mage chooses a point on the ground that they can see within 60 feet\
    \ of them. A 20-foot square of glowing, unholy energy appears on the ground centered\
    \ on that point and lasts for up to 1 minute. Each enemy in that area is vulnerable\
    \ to fire damage."
  "name": "Unhallowed Ground (3rd-Level Spell; Concentration)"
"reactions":
- "desc": "When a creature the mage can see within 60 feet of them casts a spell,\
    \ the mage reflects some of the spell's magical energy back at the caster. The\
    \ caster must succeed on a DC 14 Dexterity saving throw or take 3 (1d6) force\
    \ damage per level of the triggering spell (minimum 1d6 force damage)."
  "name": "Spell Siphon"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Hobgoblin%20War%20Mage.png"
```
^statblock