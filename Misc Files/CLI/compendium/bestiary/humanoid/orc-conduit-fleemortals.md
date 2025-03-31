---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
aliases: ["Orc Conduit"]
---
# [Orc Conduit](Misc Files\CLI\compendium\bestiary\humanoid/orc-conduit-fleemortals.md)
*Source: Flee, Mortals! p. 207*  

```statblock
"name": "Orc Conduit (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Artillery"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"stats":
- !!int "14"
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "16"
"speed": "35 ft."
"skillsaves":
  "Perception": !!int "3"
"damage_resistances": "determined by the conduit's affinity trait"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Orc"
"cr": "1"
"traits":
- "desc": "The conduit has a lifelong affinity for one of the following damage types:\
    \ cold, fire, or lightning. The chosen type determines the conduit's damage resistance\
    \ and the damage of their Elemental Discharge and Power Burst actions."
  "name": "Affinity"
- "desc": "When the conduit isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they are reduced to 0 hit points but not killed outright, they can make\
    \ an attack against an enemy (no action required) before the hit point reduction\
    \ is resolved. If the attack hits and its damage reduces the target to 0 hit points,\
    \ the conduit drops to 1 hit point instead of 0 hit points."
  "name": "Relentless (1/Turn)"
"actions":
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 9 (1d12 + 3) damage of the type determined by the conduit's\
    \ Affinity trait."
  "name": "Elemental Discharge (Cantrip)"
- "desc": "The conduit unleashes explosive energy in a 15-foot cone. The ground in\
    \ that area becomes difficult terrain, and each creature in that area must make\
    \ a DC 13 Dexterity saving throw. On a failed save, a creature takes 10 (3d6)\
    \ damage of the type determined by the conduit's Affinity trait, and they are\
    \ pushed 10 feet away from the conduit. On a successful save, a creature takes\
    \ half as much damage and isn't pushed."
  "name": "Power Burst (2/Day; 1st-Level Spell)"
"bonus_actions":
- "desc": "The conduit takes the Dash action."
  "name": "Rush"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Orc%20Conduit.png"
```
^statblock