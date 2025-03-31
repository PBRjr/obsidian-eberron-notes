---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey/controller
statblock: inline
aliases: ["Swamp Dryad"]
---
# [Swamp Dryad](Misc Files\CLI\compendium\bestiary\fey/swamp-dryad-fleemortals.md)
*Source: Flee, Mortals! p. 336*  

```statblock
"name": "Swamp Dryad (FleeMortals)"
"size": "Large"
"type": "fey"
"subtype": "Controller"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "171"
"hit_dice": "18d10 + 72"
"stats":
- !!int "18"
- !!int "12"
- !!int "18"
- !!int "12"
- !!int "21"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "10"
  "Strength": !!int "9"
  "Constitution": !!int "9"
"skillsaves":
  "Medicine": !!int "10"
  "Animal Handling": !!int "10"
  "Acrobatics": !!int "6"
  "Arcana": !!int "6"
  "Survival": !!int "10"
"damage_resistances": "acid; poison; bludgeoning, piercing, slashing from mundane\
  \ attacks"
"condition_immunities": "[poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Sylvan, any languages the dryad spoke before their binding"
"cr": "13"
"traits":
- "desc": "The dryad has advantage on saving throws against supernatural effects."
  "name": "Supernatural Resistance"
- "desc": "The dryad can communicate with Beasts and Plants as if they shared a language."
  "name": "Speak with Beasts and Plants"
- "desc": "The dryad can use 10 feet of movement to step into one living tree within\
    \ their reach and emerge from a second living tree within 60 feet of the first\
    \ tree, appearing in an unoccupied space within 5 feet of the second tree. Both\
    \ trees must be Large or larger."
  "name": "Tree Stride (1/Turn)"
"actions":
- "desc": "The dryad makes two Slam attacks and uses Entangling Roots, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 13\
    \ (2d8 + 4) piercing damage, and the target must make a DC 18 Constitution saving\
    \ throw. On a failed save, the target takes 14 (4d6) poison damage and is [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ for 1 minute. On a successful save, the target takes half as much damage and\
    \ isn't [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)."
  "name": "Slam"
- "desc": "The dryad chooses a point they can see within 60 feet of them, causing\
    \ tree roots to pull free of the ground and attack in a 15-foot radius centered\
    \ on that point. If the dryad is within 5 feet of their tree, the radius of this\
    \ effect doubles to 30 feet. Each creature in that area must succeed on a DC 18\
    \ Strength saving throw or take 22 (4d10) bludgeoning damage and be [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 14).\n\nWhile [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, a creature is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and their flesh begins to harden and turn to wood.\n\nAt the end of a creature's\
    \ third consecutive turn being [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ in this way, they become [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified)\
    \ and turn into a hardwood statue. The [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified)\
    \ condition ends for that creature if the dryad uses an action to end it, or if\
    \ the dryad dies."
  "name": "Entangling Roots (Recharge 5-6)"
- "desc": "The dryad targets up to five creatures they can see within 30 feet of them.\
    \ Each target who can see the dryad must succeed on a DC 18 Wisdom saving throw\
    \ or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened) of the dryad\
    \ (save ends at end of turn). If a target succeeds on their saving throw or the\
    \ effect ends for them, the target is immune to the swamp dryad's Fey Intimidation\
    \ for the next 24 hours."
  "name": "Fey Intimidation"
"bonus_actions":
- "desc": "The dryad touches a creature, who regains 18 (3d8 + 5) hit points. Alternatively,\
    \ the creature removes one disease or neutralizes one poison afflicting them."
  "name": "Swamp Medicine (3/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Swamp%20Dryad.png"
```
^statblock