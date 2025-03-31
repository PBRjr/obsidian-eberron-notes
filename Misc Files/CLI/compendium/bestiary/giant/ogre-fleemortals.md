---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/brute
statblock: inline
aliases: ["Ogre"]
---
# [Ogre](Misc Files\CLI\compendium\bestiary\giant/ogre-fleemortals.md)
*Source: Flee, Mortals! p. 198*  

```statblock
"name": "Ogre (FleeMortals)"
"size": "Large"
"type": "giant"
"subtype": "Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"stats":
- !!int "16"
- !!int "8"
- !!int "16"
- !!int "7"
- !!int "14"
- !!int "7"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "5"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Giant"
"cr": "2"
"traits":
- "desc": "When the ogre has half their hit points or fewer, they are resistant to\
    \ mundane bludgeoning, piercing, and slashing damage."
  "name": "Defiant Anger"
"actions":
- "desc": "The ogre makes one Spiked Club attack and one Fist attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) piercing damage."
  "name": "Spiked Club"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) bludgeoning damage. If the target is Medium or smaller, they are [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 13). Until this grapple ends, the ogre can't use this fist to attack\
    \ other targets. The ogre has two fists, one of which holds their club."
  "name": "Fist"
- "desc": "The ogre throws one Medium or smaller creature they are grappling up to\
    \ 30 feet horizontally. Each creature in the thrown creature's path must succeed\
    \ on a DC 13 Dexterity saving throw or take 3 (1d6) bludgeoning damage and be\
    \ knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone). After this throw,\
    \ the thrown creature takes 7 (2d6) bludgeoning damage and falls [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "People-Bowling"
"bonus_actions":
- "desc": "The ogre yells in the face of one creature within 10 feet of them. The\
    \ target must succeed on a DC 13 Wisdom saving throw or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of the ogre until the end of the ogre's next turn. A creature who succeeds on\
    \ their saving throw is immune to all ogres' Bellow for 24 hours."
  "name": "Bellow (1/Day)"
"reactions":
- "desc": "If the ogre takes damage while [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ or [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned), they end these\
    \ conditions on themself."
  "name": "Violent Focus (1/Day)"
"source":
- "FleeMortals"
```
^statblock